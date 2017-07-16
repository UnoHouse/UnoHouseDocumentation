[<-- Powrót](README.md)

# Serwisy

### Zależności

* [FosRestBundle](https://symfony.com/doc/master/bundles/FOSRestBundle/index.html)
* [FosUserBundle](http://symfony.com/doc/master/bundles/FOSUserBundle/index.html)
* [SonataAdminBundle](https://symfony.com/doc/master/bundles/SonataAdminBundle/index.html)
* [swagger-php](https://github.com/zircote/swagger-php)

### Mikroserwisy w aplikacji

##### Oparte na CQRS
* ```unohouse.repository.apk.reader``` Odczyt danych dla apk z bazy
* ```unohouse.repository.apk.witer``` Zapis danych dla apk z bazy
* ```unohouse.repository.sensor.reader``` Odczyt danych dla wartości z czujników z bazy danych
* ```unohouse.repository.sensor.witer``` Zapis danych dla wartości z czujników do bazy danych


[<-- Powrót](README.md)