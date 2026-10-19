# Production-style API Deployments

This is a reviewable example, not a one-click secure production installer. Replace `example.com`, usernames, paths and ports before use. DNS, certificates, OS patches and backups are your responsibility.

**Flow:** client HTTPS → Nginx port 443 → 127.0.0.1:8000 → Python app.
