# Glossar

## Dockerfile

Ein Dockerfile ist eine Textdatei, die Anweisungen enthält, die Docker verwenden kann, um ein Docker-Image zu erstellen. Ein Dockerfile enthält Anweisungen, die Docker verwenden kann, um ein Docker-Image zu erstellen. Ein Docker-Image ist eine ausführbare Anwendung, die alle benötigten Abhängigkeiten enthält, einschließlich des Betriebssystems, der Bibliotheken, der Tools und der Laufzeitumgebung.

#### Beispie Dockerfile

Die einzelenen Schritte in einem Dockerfile sind wie Schichten in einem Kuchen. Jede Schicht fügt dem Docker-Image etwas hinzu.
Die Schichten werden gecached, so dass sie bei der nächsten Ausführung des Dockerfiles nicht erneut ausgeführt werden müssen.

```dockerfile
# Use the official PHP image
FROM php:7.4-apache
# Install the necessary extensions
RUN docker-php-ext-install pdo_mysql
# Copy the application files
COPY . /var/www/html
# Set the working directory
WORKDIR /var/www/html
# Expose the port
EXPOSE 80
# Start the Apache server
CMD ["apache2-foreground"]
```

## Docker-Image

Ein Docker-Image ist eine ausführbare Anwendung, die alle benötigten Abhängigkeiten enthält, einschließlich des Betriebssystems, der Bibliotheken, der Tools und der Laufzeitumgebung.

## Docker-Container

Ein Docker-Container ist eine *Instanz* (gestartetes Docker Image) eines Docker-Images. Ein Docker-Container enthält eine ausführbare Anwendung, die alle benötigten Abhängigkeiten enthält, einschließlich des Betriebssystems, der Bibliotheken, der Tools und der Laufzeitumgebung.

## Docker-Compose

Docker-Compose ist ein Tool, mit dem Sie mehrere Docker-Container gleichzeitig erstellen, starten und stoppen können. Docker-Compose verwendet eine YAML-Datei, um die Konfiguration der Docker-Container zu definieren.

## Docker-Registry

Eine Docker-Registry ist ein privates Repository, in dem Docker-Images gehostet werden. Eine Docker-Registry enthält eine Vielzahl von Docker-Images, die von der Organisation erstellt wurden.

### Docker-Hub

Docker Hub ist ein öffentliches Repository, in dem Docker-Images gehostet werden. Docker Hub enthält eine Vielzahl von Docker-Images, die von der Community erstellt wurden.

### Andere Docker-Registries

- [AWS Elastic Container Registry (ECR)](https://aws.amazon.com/ecr/)
- [Google Container Registry (GCR)](https://cloud.google.com/container-registry)
- [Azure Container Registry (ACR)](https://azure.microsoft.com/en-us/services/container-registry/)
- [GitHUb Container Registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry)
