# NGINX

### Обчная конфигурация для раздачи статичного файла

```
http {
  server {
    listen 80;
    server_name localhost;

    location / {
      root /usr/share/nginx/html;
      index index.html;
    }
  }
}
```

### как раздавать proxy pass
localhost

### react pwa
