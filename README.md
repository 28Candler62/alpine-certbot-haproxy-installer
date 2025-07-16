# alpine-certbot-haproxy-installer
Alpine Certbot installer for HaProxy

- Python (certbot requires python)
- cron
    - daily with random specific time
- Find certificates in directory.
- Read certificates to identify "notAfter" date.
- Initiate renewal if close to expiring.
- Process/store new cert as required.
- HaProxy dynamic "set ssl cert" process.
- Email/notify on fault as required.
