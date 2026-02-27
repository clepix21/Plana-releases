<div align="center">

<img src="https://raw.githubusercontent.com/clepix21/Plana-releases/main/src/assets/logo.png" alt="Plana Logo" width="150" />

# Plana — Releases

[![Latest Release][release_img]][release_url]
[![Downloads][downloads_img]][release_url]
[![Platforms][platforms_img]][release_url]<br/>
[![License][license_img]][license_url]

Dépôt de distribution officiel de **Plana**, l'application de gestion de planning hospitalier.<br/>
Ce repo contient uniquement les **builds** et **mises à jour** — aucun code source.



</div>

---

## Téléchargement

Rendez-vous sur la page [**Releases**][release_url] pour télécharger la dernière version de Plana.

### Plateformes disponibles

| Plateforme | Format               | Fichier                  |
| ---------- | -------------------- | ------------------------ |
| **macOS**  | DMG / ZIP            | `Plana-0.0.6.dmg`       |
| **Windows**| Installeur / ZIP     | `Plana-Setup-0.0.6.exe` |
| **Linux**  | AppImage / DEB       | `Plana-0.0.6.AppImage`  |


## Mise à jour automatique

Plana intègre un système de **mise à jour automatique** via `electron-updater`.
L'application vérifie les nouvelles versions depuis ce dépôt et propose de les
installer directement depuis l'application.

Les fichiers `latest-mac.yml`, `latest-linux.yml` et `latest.yml` (Windows)
présents dans chaque release sont utilisés par ce mécanisme.

## À propos de Plana

Plana est une application de bureau **multiplateforme** dédiée à la gestion de
planning pour les services hospitaliers. Elle permet de :

- Créer et gérer des plannings sur des **périodes de 2 semaines**
- Gérer les **agents** et leurs contraintes (équipes, rôles, restrictions)
- **Générer automatiquement** les plannings selon les règles métier
- **Valider** les plannings en temps réel
- **Exporter** en PDF et Excel
- Suivre les **heures** et l'historique des modifications

## Licence

**Plana** est un logiciel **propriétaire** — Tous droits réservés.

Copyright © 2026 [Clément Lemaire](https://github.com/clepix21). Tous droits réservés.

Toute utilisation, copie, modification ou distribution est **strictement interdite**
sans autorisation écrite préalable.

<!-- Badges -->

[release_img]: https://img.shields.io/github/v/release/clepix21/Plana-releases?style=for-the-badge&label=Dernière%20version&color=blue
[downloads_img]: https://img.shields.io/github/downloads/clepix21/Plana-releases/total?style=for-the-badge&label=Téléchargements&color=green
[platforms_img]: https://img.shields.io/badge/Plateformes-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey?style=for-the-badge
[license_img]: https://img.shields.io/badge/licence-Propriétaire-red?style=for-the-badge

<!-- Links -->

[release_url]: https://github.com/clepix21/Plana-releases/releases
[license_url]: https://github.com/clepix21/Plana/blob/main/LICENCE
