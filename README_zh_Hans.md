<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Homarr

[![集成程度](https://apps.yunohost.org/badge/integration/homarr)](https://ci-apps.yunohost.org/ci/apps/homarr/)
![工作状态](https://apps.yunohost.org/badge/state/homarr)
![维护状态](https://apps.yunohost.org/badge/maintained/homarr)

[![使用 YunoHost 安装 Homarr](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homarr)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Homarr。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place.
It integrates with the services you use to display information on the homepage (E.g. Show upcoming Sonarr/Radarr releases).

### Features

- Integrates with services you use.
- Search the web directly from your homepage.
- Real-time status indicator for every service.
- Automatically finds icons while you type the name of a service.
- Widgets that can display all types of information.
- Very light-weight and fast.


**分发版本：** 1.8.0~ynh1

**演示：** <https://homarr.ajnart.fr/fr>

## 截图

![Homarr 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://homarr.dev/>
- 官方用户文档： <https://homarr.dev/docs/about>
- 官方管理文档： <https://homarr.dev/docs/about>
- 上游应用代码库： <https://github.com/homarr-labs/homarr>
- YunoHost 商店： <https://apps.yunohost.org/app/homarr>
- 报告 bug： <https://github.com/YunoHost-Apps/homarr_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/homarr_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
或
sudo yunohost app upgrade homarr -u https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
