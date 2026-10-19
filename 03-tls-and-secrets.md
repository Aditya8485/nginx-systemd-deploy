# HTTPS and secrets

Obtain certs using a maintained ACME client (Certbot is one option), after DNS and port 80 connectivity work. Check renewal on your specific setup: `sudo certbot renew --dry-run`.

Do not paste certificate private keys into Git. Keep application secrets in a protected environment file, secret manager or secure deployment mechanism. Don't log access tokens.

