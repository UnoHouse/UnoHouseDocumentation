# UnoHouse
![UnoHouse](img/unohouse.png)

Technologie:

- [Nginx-proxy](https://hub.docker.com/r/jwilder/nginx-proxy/) 
- [Apache HTTPd](https://hub.docker.com/r/webdevops/php-apache/)
- [PHP-FPM (7.0) (with Xdebug)](https://hub.docker.com/r/webdevops/php-apache/)
- [MySQL](https://hub.docker.com/_/mysql/)
- [Solr](https://hub.docker.com/_/solr/)
- [ELK, Elasticsearch, Logstash, Kibana](https://hub.docker.com/r/willdurand/elk/)
- [Redis (disabled)](https://hub.docker.com/_/redis/)
- [Memcached (disabled)](https://hub.docker.com/_/memcached/)
- [PhpMyAdmin Docker image](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)
- [Jenkins](https://jenkins.io/)

## Docker - dokumentacja

- [Technologie](/documentation/pl/Docker/TECH.md)
- [Instalacja, wymagania](/documentation/pl/Docker/INSTALL.md)
- [Serwisy, konfiguracja](/documentation/pl/Docker/SERVICES.md)
- [Wprowadzanie zmian](/documentation/CUSTOMIZE.md)
- [Uruchomienie aplikacji](/documentation/STARTUP.md)
- [Szczegółowe info](/documentation/INFO.md)

## PHP - dokumentacja
- [Technologie](/documentation/pl/PHP/TECH.md)
- [Instalacja, wymagania](/documentation/pl/PHP/INSTALL.md)
- [Serwisy, konfiguracja](/documentation/pl/PHP/SERVICES.md)
- [Wprowadzanie zmian](/documentation/pl/PHP/CUSTOMIZE.md)
- [Uruchomienie aplikacji](/documentation/pl/PHP/DOCKER-STARTUP.md)
- [Szczegółowe info](/documentation/pl/PHP/INFO.md)

## Mikrokontroler - dokumentacja
- [Technologie](/documentation/pl/Mikrokontroller/TECH.md)
- [Instalacja, wymagania](/documentation/pl/Mikrokontroller/INSTALL.md)
- [Serwisy, konfiguracja](/documentation/pl/Mikrokontroller/SERVICES.md)
- [Wprowadzanie zmian](/documentation/pl/Mikrokontroller/CUSTOMIZE.md)
- [Uruchomienie aplikacji](/documentation/pl/Mikrokontroller/DOCKER-STARTUP.md)
- [Szczegółowe info](/documentation/pl/Mikrokontroller/INFO.md)

## Mikroprocesor - dokumentacja
- [Technologie](/documentation/pl/Mikroprocesor/TECH.md)
- [Instalacja, wymagania](/documentation/pl/Mikroprocesor/INSTALL.md)
- [Serwisy, konfiguracja](/documentation/pl/Mikroprocesor/SERVICES.md)
- [Wprowadzanie zmian](/documentation/pl/Mikroprocesor/CUSTOMIZE.md)
- [Uruchomienie aplikacji](/documentation/pl/Mikroprocesor/DOCKER-STARTUP.md)
- [Szczegółowe info](/documentation/pl/Mikroprocesor/INFO.md)

## Android - dokumentacja
- [Technologie](/documentation/pl/Android/TECH.md)
- [Instalacja, wymagania](/documentation/pl/Android/INSTALL.md)
- [Serwisy, konfiguracja](/documentation/pl/Android/SERVICES.md)
- [Wprowadzanie zmian](/documentation/pl/Android/CUSTOMIZE.md)
- [Uruchomienie aplikacji](/documentation/pl/Android/DOCKER-STARTUP.md)
- [Szczegółowe info](/documentation/pl/Android/INFO.md)

## Frontend - dokumentacja
- [Technologie](/documentation/pl/Frontend/TECH.md)
- [Instalacja, wymagania](/documentation/pl/Frontend/INSTALL.md)
- [Serwisy, konfiguracja](/documentation/pl/Frontend/SERVICES.md)
- [Wprowadzanie zmian](/documentation/pl/Frontend/CUSTOMIZE.md)
- [Uruchomienie aplikacji](/documentation/pl/Frontend/DOCKER-STARTUP.md)
- [Szczegółowe info](/documentation/pl/Frontend/INFO.md)

### About project
This is a project that combine couple programming languages and technologies into one fully cooperational organism.

##### 1. C/C++
Used to manage microcontroller, in this case Arduino Mega2560
##### 2. Java
Maintain microprocessor part. Now it's a Raspberry Pi 2b+
##### 3. Android
Used to create mobile application that will help manage system from mobile device.
##### 4. PHP
Server part. PHP is used to manage api for microprocessor and mobile device. 
It manage data stored in DB and allow to view result in web brower from admin panel.

### About sensors
Sensors used in this project are simple integrated boards to manage basic parameters.
* DHT11 for temperature and humidity,
* PIR sensor - infrared sensor that work as alarm sensor and light switcher,
* HC-SR 04 - Sensor that work as parking aid, it allows to detect distance to object,
* Water leak sensor - to check if there is no flood in home (i.e. bathroom),
* Gas sensor - used mosty in kitchen, check for carbon oxide level in air,
* IR sensor to receive data from remote pilots,
* Capacity resistor - check if mailbox contain any letters,
* Noise detector - to check if there is no 
* Glass break detector
* Closed door detector
* Light sensor - to check daytime.

### Drivers
* Door controll - to close/open doors. servomechanism,
* Temperature controller,
* Window controller - to controll Window blinds,
* Light controller - to turn on/off light in room
* Sprinklers controller,
* Home flowers sprinklers,

### Concept
Unohouse aim to be simple and effective system that allow to save some time durning daily and nighty life.
Base concept is to learn and use technologies that help us everyday. 
From simple light management system to complex wieght calcutaion and sprinklers systems automate and schedule daily responsibilities.
