```bash
DATABASE_URL=postgresql://zorvixeuser:zorvixepassword@127.0.0.1:5432/zorvixedatabase
```

```bash
 nano /etc/nginx/sites-available/app.zorvixetechnologies.com.conf
```

```bash
nano /etc/nginx/sites-available/api.zorvixetechnologies.com.conf
```

```bash
nano /etc/nginx/sites-available/zorvixetechnologies.com.conf
```

```bash
certbot --nginx -d zorvixetechnologies.com -d www.zorvixetechnologies.com -d app.zorvixetechnolo
gies.com -d api.zorvixetechnologies.com
```
