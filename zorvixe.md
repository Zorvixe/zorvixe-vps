```bash
DATABASE_URL=postgresql://zorvixeuser:zorvixepassword@127.0.0.1:5432/zorvixedatabase
```

```bash
 nano /etc/nginx/sites-available/app.zorvixetechnologies.in.conf
```

```bash
nano /etc/nginx/sites-available/api.zorvixetechnologies.in.conf
```

```bash
nano /etc/nginx/sites-available/zorvixetechnologies.in.conf
```

```bash
certbot --nginx -d zorvixetechnologies.in -d www.zorvixetechnologies.in -d app.zorvixetechnologies.in -d api.zorvixetechnologies.in
```
