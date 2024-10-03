# Docker-React-Projekt

Dieses Projekt demonstriert die Containerisierung einer React-Anwendung mit Docker und die Automatisierung des Build- und Push-Prozesses mit GitHub Actions.

## Vorgehen auf Dockerhub pushen & Github Registry

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
## Github Container Registry
![image](https://github.com/user-attachments/assets/6af3a4c6-9585-4afd-a698-0ce8493efb1a)
![image](https://github.com/user-attachments/assets/77fef3b6-7122-45a2-a97a-dba4c5b8110d)


### DockerHub Repository
![image](https://github.com/user-attachments/assets/fb6f2673-f131-4a7e-a7dd-09f97381d19f)
![image](https://github.com/user-attachments/assets/92a61a14-a90b-4e35-a8ce-64ff4460ac39)

## Vorgehen AWS
1. Enviromnet Variablen erstellen und mit Daten befüllen
   - AWS_ACCESS_KEY_ID
   - AWS_SECRET_ACCESS_KEY
   - AWS_SESSION_TOKEN
   - AWS_REGION
   - ECR_REPOSITORY
2. AWS aufsetzen
   - Repository 
   - Cluster 
   - Taskdefinition
   - Service
3. Im YAML File von der AWS Pipeline "Update ECS service" task mit Namen der zuvor erstellten AWS Services anpassen

## AWS Ergebnisse

### Elastic Container Registry mit refcard image
![image](https://github.com/user-attachments/assets/b4ecb5ec-3986-49d8-ae89-a66ad4ae4144)

### Cluster:
![image](https://github.com/user-attachments/assets/cb580353-8574-495b-9121-297be9bb8e83)

### Taskdefinition:
![image](https://github.com/user-attachments/assets/5277395a-266d-4a1c-abd5-43e0657749f0)

### Service:
![image](https://github.com/user-attachments/assets/998e7128-eb99-4b37-bafc-430547b6504f)

### AWS Github Pipeline
![image](https://github.com/user-attachments/assets/8fca92e8-bf52-4d9b-9f69-7324d33e7edf)



