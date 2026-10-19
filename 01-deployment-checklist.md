# First deployment checklist

- [ ] DNS A/AAAA points to the server
- [ ] Application runs under a non-root user
- [ ] API listens on 127.0.0.1 behind reverse proxy
- [ ] Service auto-starts after reboot
- [ ] Nginx config validated with `sudo nginx -t`
- [ ] Firewall allows actual SSH port, HTTP 80 and HTTPS 443
- [ ] HTTPS certificate installed; renewal tested
- [ ] Logs, backups, monitoring and rollback documented

## Useful commands

