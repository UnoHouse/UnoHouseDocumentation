[<-- Powrót](README.md)

# Serwisy

### unohouse-app (PHP, Apache HTTPd, PHP_FPM)

Typ           | Wartość
------------- | -------------
Host          | app:80, app:443 (ssl)
External Port | 8000, 8443 (ssl)

### unohousedb - MySQL

Typ           | Wartość
------------- | -------------
User          | unohouse
Password      | unohouse
Database      | unohouse
Host          | mysql:3306
External Port | 13306

### Solr

Typ           | Wartość
------------- | -------------
Host          | solr:8983
External Port | 18983
Cores         | docker/solr/conf/solr.xml (data dirs are created automatically)

### Elasticsearch (disabled by default)

Typ           | Wartość
------------- | -------------
Host          | elasticsearch:9200 and :9300
External Port | 19200 and 19300

### Redis

Typ           | Wartość
------------- | -------------
Host          | redis
Port          | 6379

### Memcached

Typ           | Wartość
------------- | -------------
Host          | memcached
Port          | 11211

### FTP

Typ           | Wartość
------------- | -------------
Host          | ftp
Ports         | 20,21
User          | unohouse
Password      | unohouse
Path          | /storage/ftp (if not changed in env)

### PhpMyAdmin

Typ           | Wartość
------------- | -------------
Host          | phpmyadmin
Ports         | 8001
Log in server | unohousedb
Username      | unohouse
Password      | unohouse

[<-- Powrót](README.md)