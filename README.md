- Set-up your traefik to 11000 port
- docker-compose up -d
- go to https://nextcloud.local.:8080/
- start set-up
- go to reverse-proxy domain https://nextcloud.duckdns.org/login
- after start use https://nextcloud.mikrotik24.duckdns.org/settings/admin/overview

- User default admin account to access AIO UI -> settings -> Overview
- After the successful run use `docker system prune --volumes --all` to free disk space
