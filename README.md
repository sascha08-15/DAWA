# DAWA
Dies ist die Anleitung für die Lehrveranstaltung DAWA.
Die wesentlichen Schritte werden hier beschrieben. Da die verwendete Software Änderungen unterliegt, gelten zusätzlich als Hilfestellung
* Aktuelle Dokumentation von Docker: https://docs.docker.com/get-started/introduction/
* Aktuelle Dokumentation von Git: https://git-scm.com/doc
* Aktuelle Dokumentation von Superset: https://superset.apache.org/docs/quickstart/


# Voraussetzungen
* Installieren Sie Docker
* Installieren Sie Git
* Starten Sie Docker (Deamon oder Docker Desktop, je nachdem Ob Windows, Linux oder MacOS genutzt wird)
  
# Apache Superset über Docker Compose starten
* Clonen Sie das Repository mit ```git clone https://github.com/apache/superset.git```
* Starten Sie Apache Superset mit ```docker compose up```

# Verfügbare Services umfassen nun:
* Die Apache Superset umgebung auf URL http://localhost:8088
* Eine Postgres Beispiel Datenbank
