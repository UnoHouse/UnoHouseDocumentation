[<-- Powrót](README.md)

# Technologie

* Apache 2.4 - hostuje vritualne hosty dla:
    - Głównej apliakcji
    - Dokumentacji swaggera
    - Proxy dla Jenkins'a
* PHP 7.1 z PHP-FPM
    - Wykorzystanie przez Symfony 3.x
* Mysql 5.7
    - Wraz z Doctrine
* Memcached
    - Przechowuje dane które są wielokrotnie przetwarzane w celu odciążenia bazy, głównie stałe do obsługi obliczeń.
* ELK
    - ElasticSearch
        - Wykorzystywany do przechowywania danych z czujników.
    - Kibana
        - Jeszcze się okaże :)
    - Logstash
        - Analizotor logów z REST API,

Przed serwerem Apache stoi NGIX-proxy które rozdziela ruch dla 
poszczególnych adresów. Dzięki temu możliwe jest utrzymanie 
wielu kontenerów [Docker'a](https://www.docker.com/) 
bez potrzeby tworzenia systemu zapychającego serwer zbednymi 
apliakcjiami. Każda z wymienionych technologi pomaga w procesie
obróbki danych. 

## Testy
Do testów wykorzystujemy Jenkins'a który przeprowadza buildy 
oraz testy na posczególnych aplikacjach. POmaga w zbudowaniu
aplikacji dla REST API jak i wspomaga proces tworzenia osobnych
narzędzi, front, Android app, Testy kodu dla mikroprocesora.

[<-- Powrót](README.md)