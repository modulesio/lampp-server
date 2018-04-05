# lampp-server
Lampp Server - Ubutu 14.04, apache, mysql, php, phpmyadmin

# to custom vhost
Add - ./apache2/sites-available:/etc/apache2/sites-available in volumes

```
...
   volumes:
   - ./public:/var/www/html
   - ./apache2/sites-available:/etc/apache2/sites-available 
```
