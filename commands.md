# Contabo server

```
sudo apt update
sudo apt install nginx
sudo systemctl start nginx
sudo systemctl status nginx
sudo nano /var/www/html/index.html
```

```
<!DOCTYPE html>
<html>
<body>
    <h1>Helo World</h1>
</body>
</html>
```

useful linux commands:

```
pwd
```

## TO DO

https://certbot.eff.org/

nvm install node

install pm2 (see how to autorestart)

reverse proxy nginx (/etc/nginx/...sites-available/http.conf <-- set rule if /api -> redirect \*:3306
