# Instalacja

## Wymagania

- [git](https://git-scm.com/)
- [composer](https://getcomposer.org/)
- [docker-compose](https://github.com/docker/compose)


## Uruchomienie

```bash
git clone --recursive https://github.com/UnoHouse/UnoHouseDocker UnoHouseDocker

cd UnoHouseDocker
```
Tutuaj możesz wybrać tryb pracy dla środowisk **PROD**
```
cp docker-compose.prod.yml docker-compose.yml
docker-compose build
docker-compose up -d
```
 lub **DEV**
```
cp docker-compose.dev.yml docker-compose.yml
docker-compose build
docker-compose up -d
``` 
