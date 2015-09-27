# Nginx Tuning For Best Performance in WordPress

Configurations:
* [nginx](https://github.com/hyperbrains/nginx-varnish-wordpress/tree/master/nginx)
 * [security.conf](https://github.com/hyperbrains/nginx-varnish-wordpress/blob/master/nginx/conf.d/security.conf)
 * [cache.conf](https://github.com/hyperbrains/nginx-varnish-wordpress/blob/master/nginx/conf.d/cache.conf)
* [varnish 4](https://github.com/hyperbrains/nginx-varnish-wordpress/tree/master/varnish)
* [php-fpm](https://github.com/hyperbrains/nginx-varnish-wordpress/tree/master/php5-fpm)
* [ubuntu sysctl.conf](https://github.com/hyperbrains/nginx-varnish-wordpress/tree/master/ubuntu)

![Varnish-WordPress-nginx-cache](https://i.imgur.com/wwVBB1q.png)

Purge Varnish WordPress-cache: [Varnish HTTP Purge](https://wordpress.org/plugins/varnish-http-purge/)

Varnish 4 restart using service wrapper script: `service varnish restart`

Nginx 4 restart using service wrapper script: `service nginx restart`

php-fpm 4 restart using service wrapper script: `service php5-fpm restart`
