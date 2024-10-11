<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Flood voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/flood.svg)](https://ci-apps.yunohost.org/ci/apps/flood/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/flood.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/flood.maintain.svg)

[![Flood met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=flood)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Flood snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Flood is a monitoring service for rTorrent. It's a Node.js service that communicates with your favorite torrent client and serves a decent web UI for administration.

**Geleverde versie:** 4.8.2~ynh2

## Schermafdrukken

![Schermafdrukken van Flood](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://flood.js.org/>
- Officiele beheerdersdocumentatie: <https://github.com/jesec/flood/wiki>
- Upstream app codedepot: <https://github.com/jesec/flood>
- YunoHost-store: <https://apps.yunohost.org/app/flood>
- Meld een bug: <https://github.com/YunoHost-Apps/flood_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/flood_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
of
sudo yunohost app upgrade flood -u https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
