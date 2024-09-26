# Docker-React-Projekt

Dieses Projekt demonstriert die Containerisierung einer React-Anwendung mit Docker und die Automatisierung des Build- und Push-Prozesses mit GitHub Actions.

## Vorgehen

1. Erstellung des Dockerfiles
   - Verwendung eines mehrstufigen Builds
   - Node.js für den Build-Prozess
   - Nginx als leichtgewichtiger Webserver für die Produktion

2. Konfiguration der GitHub Actions
   - Erstellung der docker-publish.yml Workflow-Datei
   - Automatisierung des Build- und Push-Prozesses bei Änderungen im main-Branch

3. Einrichtung der DockerHub-Verbindung
   - Speicherung der DockerHub-Zugangsdaten als GitHub Secrets

4. Testen und Verifizierung
   - Lokaler Build und Test des Docker-Images
   - Push zu DockerHub über GitHub Actions

## Ergebnisse

### GitHub Actions Workflow
![image](https://github.com/user-attachments/assets/9ca18124-1b81-4d05-b354-8f265d0753d3)


### DockerHub Repository
![image](https://github.com/user-attachments/assets/fb6f2673-f131-4a7e-a7dd-09f97381d19f)
