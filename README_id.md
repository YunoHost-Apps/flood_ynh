<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Flood untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/flood)](https://ci-apps.yunohost.org/ci/apps/flood/)
![Status kerja](https://apps.yunohost.org/badge/state/flood)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/flood)

[![Pasang Flood dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=flood)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Flood secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Flood is a monitoring service for rTorrent. It's a Node.js service that communicates with your favorite torrent client and serves a decent web UI for administration.

**Versi terkirim:** 4.9.3~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Flood](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://flood.js.org/>
- Dokumentasi admin resmi: <https://github.com/jesec/flood/wiki>
- Depot kode aplikasi hulu: <https://github.com/jesec/flood>
- Gudang YunoHost: <https://apps.yunohost.org/app/flood>
- Laporkan bug: <https://github.com/YunoHost-Apps/flood_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/flood_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
atau
sudo yunohost app upgrade flood -u https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
