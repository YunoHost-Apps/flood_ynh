<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Flood

[![集成程度](https://dash.yunohost.org/integration/flood.svg)](https://ci-apps.yunohost.org/ci/apps/flood/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/flood.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/flood.maintain.svg)

[![使用 YunoHost 安装 Flood](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=flood)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Flood。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Flood is a monitoring service for rTorrent. It's a Node.js service that communicates with your favorite torrent client and serves a decent web UI for administration.

**分发版本：** 4.8.2~ynh3

## 截图

![Flood 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://flood.js.org/>
- 官方管理文档： <https://github.com/jesec/flood/wiki>
- 上游应用代码库： <https://github.com/jesec/flood>
- YunoHost 商店： <https://apps.yunohost.org/app/flood>
- 报告 bug： <https://github.com/YunoHost-Apps/flood_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/flood_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
或
sudo yunohost app upgrade flood -u https://github.com/YunoHost-Apps/flood_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
