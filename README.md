### MYSQL INSTALLER

```
docker-compose up
```

**if you hit errors creating folders or mounts you need to restart your docker engine on windows!**

#### Installing wordpress for real

Navigate to the public_html folder
Run the following

```
composer install
composer exec wp core download
```

Copy the sample wp-config-sample.php to wp-config.php and update accordingly!

```
php -dxdebug.start_with_request=false -S localhost:7676 routing.php
```