
# Hosting

## Webhosting

- Das Betriebssystem wird durch den Hoster Verwaltet
- Update von PHP und MySQL wird durch den Hoster Verwaltet
- Kein Zugriff auf die Konsole
- Kein Zugriff auf die Datenbank
- Kein Zugriff auf die PHP Konfiguration

### Beispiel Hoster Webhosting

- [1&1](https://www.1und1.de/)
- [Strato](https://www.strato.de/)
- [HostEurope](https://www.hosteurope.de/)
- [All-Inkl](https://all-inkl.com/)
- [DomainFactory](https://www.df.eu/)
- [GoDaddy](https://de.godaddy.com/)

## VPS - Virtual Private Server

### Merkemale

- Zugriff auf die Konsole
- Man ist selbst für die Updates von PHP und MySQL verantwortlich
- Zugriff auf die Datenbank
- Zugriff auf die PHP Konfiguration

### Beispiel Hoster VPS

- <https://contabo.com/de/>
- <https://www.hetzner.de/>
- <https://www.netcup.de/>

## Cloud Hosting

### Merkemale des Cloud Hostings

- Zugriff auf die Konsole
- Man ist selbst für die Updates von PHP und MySQL verantwortlich
- Zugriff auf die Datenbank
- Zugriff auf die PHP Konfiguration
- Skalierbar
- Hohe Verfügbarkeit
- Hohe Sicherheit
- Hohe Performance
- Pay as you go
- Erhöhte Komplexität (Kosten, Sicherheit, Performance, Skalierbarkeit)
- IaC (Infrastructure as Code) mit Terraform, CloudFormation, Ansible, Puppet, Chef, Salt, etc.

## On-Premise

### Merkemale on-Premise

- Man ist selbst für die Updates der Hardware verantwortlich.
- Man ist selbst für die Updates der Software verantwortlich.
- Man ist für die Datensicherheit verantwortlich.
- Man ist für die Performance verantwortlich.
- Im Vergleich zum Cloud-Hosting ist die Skalierbarkeit begrenzt.

## Docker Hosting

Verschieden Varianten von Docker Hosting:

1. On-Premise Docker Hosting
2. Cloud Docker Hosting (z.B. AWS ECS, Azure Container Instances, Google Cloud Run)
3. VPS mit installiertem Docker
4. Docker Hosting Provider (z.B. DigitalOcean, Linode, Vultr, Hetzner Cloud, Contabo)

### Vorteile des Docker Hostings der verschiedenen Varianten

- Isolation der Anwendungen
- Einfache Bereitstellung von Anwendungen
- Einfache Skalierbarkeit
- Einfache Wartung
- Einfache Migration
- Einfache Sicherung
- Einfache Wiederherstellung
- Einfache Integration in CI/CD Pipelines

### Vorteile des Docker-Images

Das Docker-Image von SnipeIT enthält alles, was benötigt wird, um SnipeIT zu betreiben. Das Docker-Image enthält Apache, PHP mit den notwendigen Extensions und SnipeIT ansich.
