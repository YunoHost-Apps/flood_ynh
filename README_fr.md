<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Flood pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/flood.svg)](https://dash.yunohost.org/appci/app/flood) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/flood.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/flood.maintain.svg)

[![Installer Flood avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=flood)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Flood rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Flood is a monitoring service for rTorrent. It's a Node.js service that communicates with your favorite torrent client and serves a decent web UI for administration.

**Version incluse :** 4.8.2~ynh1

## Captures d’écran

![Capture d’écran de Flood](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://flood.js.org/>
- Documentation officielle de l’admin : <https://github.com/jesec/flood/wiki>
- Dépôt de code officiel de l’app : <https://github.com/jesec/flood>
- YunoHost Store : <https://apps.yunohost.org/app/flood>
- Signaler un bug : <https://github.com/YunoHost-Apps/flood_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/flood_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
ou
sudo yunohost app upgrade flood -u https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
