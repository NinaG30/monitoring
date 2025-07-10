# Monitoring avec Prometheus & Grafana

Ce dépôt met en place un système de monitoring basé sur **Prometheus** et **Grafana**, permettant d'observer :

- Les ressources système de la machine hôte (via `node_exporter`)
- Les métriques exposées par une application (ici, `atoolbox`) via un reverse proxy NGINX

## 📁 Structure du projet

├── docker-compose.yml
├── prometheus/
│ └── prometheus.yml
└── README.md

## But du projet

Stack utilisée dans mon projet d'entreprise pour ma formation 'Administrateur Système DevOps' afin de valider mon bloc de compétence concernant la surveillance d'une application déployée dans le cloud.

