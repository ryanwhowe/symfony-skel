# Symfony Skeleton layout
----
This is a simple layout for developing a symfony (or any other php application) in docker with a nginx server, php-fmp and mysql as your database.  There are good base build files to generate a docker container for the nginx service and the php-fpm service


## php Container
----
#### Included
* symfony cli
* composer
* xdebug
* opcache
* acpu
* pdo

## Things To Change
----
1.) update the Dockerfile-php to the php version that you would like to develop against, the default is currently php 7.3
2.) if you have a specific setup for the server that you are deploying to those settings should be pulled into the php.ini as well as the nginx setup
