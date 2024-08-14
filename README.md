# SnipeIT

Snipe-IT ist ein kostenloses, Open-Source-IT-Asset-Management-System, das in PHP geschrieben ist. Mit diesem Docker-Compose-File können Sie Snipe-IT einfach auf Ihrem lokalen Rechner ausführen.

## Inhaltsverzeichnis

1. [Glossar](./docs/00_Glossar.md)
2. [Einleitung](./docs/01_Einleitung.md)
3. [Vorraussetzungen](./docs/02_Vorraussetzungen.md)
4. [Hosting](./docs/03_Hosting.md)
5. [Infrastruktur](./docs/04_Infrastruktur.md)

## Usage

### Start the container

First, clone the repository and then run the following command:

```bash
docker compose up -d
```

- Open the browser and go to <http://localhost:8080>.
- To get access to the mailhog, go to <http://localhost:8025>.

### Restart the container

```bash
docker compose down && docker compose up -d
```

### Generate app key

```bash
docker compose run --rm app php artisan key:generate --show
```

---
