# WordPress Docker Project

Ce projet déploie un site WordPress localement en utilisant Docker et Docker Compose. Il fonctionne à la fois sur Windows et Linux (WSL2).

## Fonctionnalités

- WordPress dernière version
- Base de données MySQL
- Volumes Docker pour la persistance (`wp-content`)
- Configuration facile avec Docker Compose
- Compatible Windows et Linux

## Prérequis

- Docker Desktop (Windows) ou Docker & Docker Compose (Linux/WSL2)
- Git (optionnel pour versionning)

## Installation et lancement

1. Cloner le projet :
```bash
git clone https://github.com/tonpseudo/wordpress-docker.git
cd wordpress-docker