# UnoHouse
![UnoHouse](img/unohouse.png)

Projekt ma na celu pokazanie jak różne jezyki programowania moga wpłynąć na środowisko dookoła nas.
Dzięki połączeniu mikro-urządzeń do sterowania procesami domu oraz z aplikacją mobilna i przeglądarkową, mozliwe jest zdalne zarządzanie swoim domem.
Oprogramowanie to powstaje w celu przedstawienia sposobu komunikacji oraz współpracy zupełnie różnych technologii.
Dzięki temu możemy z łatwościa, sprawdzić czy nasz dom jest bezpieczny, oraz czy nie doszło do żadnych niespodziewanych wypadków, jak pożar.
Jeżli np. zapomnimy wyłączyć żelazko, zamiast wracać do domu, możemy w danym pomieszczeniu odłączyć prąd w gniazdkach.


##Technologie:

- [Docker](https://www.docker.com/)
- [Nginx-proxy](https://hub.docker.com/r/jwilder/nginx-proxy/) 
- [Apache HTTPd](https://hub.docker.com/r/webdevops/php-apache/)
- [PHP-FPM (7.0) (with Xdebug)](https://hub.docker.com/r/webdevops/php-apache/)
- [MySQL](https://hub.docker.com/_/mysql/)
- [ELK, Elasticsearch, Logstash, Kibana](https://hub.docker.com/r/willdurand/elk/)
- [Redis (wylączony)](https://hub.docker.com/_/redis/)
- [Memcached](https://hub.docker.com/_/memcached/)
- [PhpMyAdmin Docker](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)
- [Jenkins](https://jenkins.io/)

##Dokumentacja
- [Docker](/documentation/pl/Docker/README.md)
- [PHP](/documentation/pl/PHP/README.md)
- [Mikrokontroler (C/C++)](/documentation/pl/Mikrokontroller/README.md)
- [Mikroprocesor(Java)](/documentation/pl/Mikroprocesor/README.md)
- [Android](/documentation/pl/Android/README.md)
- [Frontend](/documentation/pl/Frontend/README.md)


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
