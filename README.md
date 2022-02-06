# phpmyadmin-curl-export

This is a fork of [the original phpmyadmin-curl-export by morawskim](https://github.com/morawskim/phpmyadmin-curl-export) which has not been maintained for a long time.
This version fixes issues with current versions of phpMyAdmin.

## REQUIREMENTS

* curl
* coreutils
* grep

## USAGE

Simple usage

````shell
phpmyadmin-curl-export --auth-type-cookie --dbname-example --phpmyadmin-user-example --phpmyadmin-password-example --host-http://localhost/phpMyAdmin
````

Enable compression

````shell
phpmyadmin-curl-export --auth-type-cookie --dbname-example --phpmyadmin-user-example --phpmyadmin-password-example --host-http://localhost/phpMyAdmin --compression
````

Add DROP TABLE / VIEW / PROCEDURE / FUNCTION / EVENT / TRIGGER statement

````shell
phpmyadmin-curl-export --auth-type-cookie --dbname-example --phpmyadmin-user-example --phpmyadmin-password-example --host-http://localhost/phpMyAdmin --add-drop
````
