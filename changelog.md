## 1.1 (2020-04-13)

Wprowadzono zmiany dot. bezpieczeństwa w security.conf

``
Header always set X-Content-Type-Options: "nosniff"
Header always set X-Frame-Options: "DENY"
Header set Strict-Transport-Security: "max-age=31536000; includeSubDomains; pre$
``

## 1.0 (2020-04-09)

Inicjalna wersja produkcyjna. Aktualizacja do grav 1.7 i php 7.4

## 0.1

Testowa inicjalna wersja


