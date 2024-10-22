# Config CRON

```
0 0 * * * certbot renew --webroot -w /var/www/certbot --quiet && nginx -s reload
```