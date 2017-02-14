# docker-php-fpm-lighttpd

## Example
```
FROM iamterence/docker-php-fpm-lighttpd:latest

# Copy source files to container
COPY . /var/www/localhost
RUN chown -R www-data. /var/www/localhost/
```
