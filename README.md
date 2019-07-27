# nextcloud
Nextcloud


# Post Install Steps

- Enable External Storage
- Exec into container
    - `chown -R www-data:root /testing`
    - `chmod -R 775 /testing`
    - Use chmod 600 to disable access to cetain folder and change owner to root
- Add `/testing` to external storage section, enable sharing, etc
- Add theming
