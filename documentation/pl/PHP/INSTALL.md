[<-- Powrót](README.md)

# Instalacja

### wymagania

* git
* composer
* Apache, Mysql, PHP serwer/container

### Instalacja
Proces przebiega bez problemowo przy użyciu standardowego zestawu komend.
```bash
git clone repo [UnoHouseDocker/www]
cd [UnoHouseDocker/www]
composer install
php bin/console doctrine:database:create
php bin/console doctrine:schema:update --force
```
Nastepnie po uruchomieniu Kontenerów dockera należy dodać do hosts
```
0.0.0.0 unohouse.dev docs.unohouse.dev
```
w celu ustawienia adresu dla aplikacji.

I to w sumie tyle. Have Fun :)

[<-- Powrót](README.md)