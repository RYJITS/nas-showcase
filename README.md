# NAS

## Presentation

NAS est presente ici sous une forme publique limitee, sans secrets ni donnees privees.

## Demarrage rapide

### Pre-requis

- Git installe localement.

### Installer et lancer

```powershell
git clone https://github.com/RYJITS/nas-showcase.git
cd nas-showcase
```

## Installation locale

Cette vitrine contient uniquement la documentation generale partageable. Pour la consulter localement:

```powershell
git clone https://github.com/RYJITS/nas-showcase.git
cd nas-showcase
Get-Content README.md
```

Aucune configuration serveur privee, adresse reseau ou sauvegarde operationnelle n'est incluse.

## Lancement

Cette vitrine documentaire ne lance aucun service. Les configurations et procedures operationnelles detaillees restent dans le depot prive.

## Utilisation

Lire `README.md` pour la vue d'ensemble, `FICHE_PROJET.md` pour les fonctions, `INSTALLATION_FR.md` pour les pre-requis generaux et `CHANGELOG_FR.md` pour les evolutions. Le deploiement reel s'appuie sur des fichiers prives absents de cette vitrine.

## Concept

Documentation d'infrastructure pour le serveur personnel: Docker, n8n, PostgreSQL, Caddy, Tailscale, Nextcloud et sauvegardes.

Rendre les procedures serveur et sauvegardes faciles a retrouver, verifier et maintenir.

Public vise: Usage interne: infrastructure, stockage, automatisations serveur et recuperation.


## Fonctionnement de l'application

Le projet ne lance pas une application publique: il sert de manuel operationnel. Les documents indiquent les chemins serveur, les commandes docker compose, les validations Caddy, les logs, les dossiers de donnees et les gestes de recuperation. Il permet donc de retrouver rapidement comment redemarrer les services, verifier l'etat du serveur ou comprendre la structure des sauvegardes.

## Fonctions de l'application

- Documente le serveur Debian et les services Docker.
- Regroupe les procedures n8n, Nextcloud, Caddy et Tailscale.
- Explique la sauvegarde automatique et les actions de maintenance.
- Reste prive par defaut.

## Actualisations et evolution

- Ajout des procédures de sauvegarde automatique et de restauration
- Clarification des configurations réseau et des redirections de port
- Mise à jour des commandes utiles et des logs de maintenance

## Comment le projet a ete reflechi et construit

Il a ete concu comme un espace prive et pratique. La structure privilegie les procedures lisibles, les reperes de maintenance et la separation entre documentation generale et parametres sensibles.

### Outils, IA et moteurs utilises

- Serveur Debian
- Docker Compose
- n8n
- PostgreSQL
- Nextcloud
- Caddy reverse proxy
- Tailscale
- Script de backup
- Cron serveur
- Logs de sauvegarde
- Debian 12
- Scripts shell et documentation Markdown

### Options techniques detectees

- Options techniques a documenter.

### Stack et dependances principales

- NAS/Documentation
- Debian 12
- Docker Compose
- n8n
- PostgreSQL
- Caddy reverse proxy
- Tailscale
- Nextcloud
- Scripts shell et documentation Markdown

### Scripts disponibles

- Aucun script detecte.

### Dependances applicatives

- Aucune dependance applicative detectee.

### Dependances de developpement

- Aucune dependance de developpement detectee.

## Automatisations et comportements internes

- Sauvegarde automatique par script shell
- Dump SQL Nextcloud/MariaDB
- Compression tar.gz des donnees
- Purge des sauvegardes anciennes
- Journalisation des sauvegardes
- Execution nocturne planifiee par cron

## Captures d'ecran

Aucune capture publique n'est disponible pour ce projet.

## Variables d'environnement

Aucune variable d'environnement n'est requise d'apres les fichiers publies.

## Securite

Ne jamais publier `.env`, tokens, sessions, logs sensibles, cles privees ou donnees personnelles.
