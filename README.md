# Installing Laufometer
## 1. Einträge in Hosts Datei einfügen.
`C:\Windows\System32\drivers\etc\hosts`
```
127.0.0.1 laufometer.local
127.0.0.1 api.laufometer.local
```
## 2. Projekt Klonen so dass wir folgende Struktur haben:
```
/laufometer
    /laufometer-frontend
    /laufometer-backend
    /laufometer-setup
```
## 3. docker-compose.yml aus dem laufometer-setup in laufometer kopieren
```
/laufometer
    /laufometer-frontend
    /laufometer-backend
    /laufometer-setup
docker-compose.yml
```
## 4. Im /laufometer mit der cmd docker-compose up -d ausführen
