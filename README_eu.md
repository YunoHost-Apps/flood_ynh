<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Flood YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/flood.svg)](https://ci-apps.yunohost.org/ci/apps/flood/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/flood.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/flood.maintain.svg)

[![Instalatu Flood YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=flood)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Flood YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Flood is a monitoring service for rTorrent. It's a Node.js service that communicates with your favorite torrent client and serves a decent web UI for administration.

**Paketatutako bertsioa:** 4.8.2~ynh3

## Pantaila-argazkiak

![Flood(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://flood.js.org/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/jesec/flood/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/jesec/flood>
- YunoHost Denda: <https://apps.yunohost.org/app/flood>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/flood_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/flood_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
edo
sudo yunohost app upgrade flood -u https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
