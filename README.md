<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Flood for YunoHost

[![Integration level](https://dash.yunohost.org/integration/flood.svg)](https://dash.yunohost.org/appci/app/flood) ![Working status](https://ci-apps.yunohost.org/ci/badges/flood.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/flood.maintain.svg)  
[![Install Flood with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=flood)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Flood quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Flood is a monitoring service for various torrent clients. It's a Node.js service that communicates with your favorite torrent client and serves a decent web UI for administration.

**Shipped version:** 4.7.0~ynh2

## Screenshots

![Screenshot of Flood](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://github.com/jesec/flood>
* Official admin documentation: <https://github.com/jesec/flood/wiki>
* Upstream app code repository: <https://github.com/jesec/flood>
* YunoHost documentation for this app: <https://yunohost.org/app_flood>
* Report a bug: <https://github.com/YunoHost-Apps/flood_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/flood_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
or
sudo yunohost app upgrade flood -u https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
