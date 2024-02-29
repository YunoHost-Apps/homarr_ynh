<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Homarr for YunoHost

[![Integration level](https://dash.yunohost.org/integration/homarr.svg)](https://dash.yunohost.org/appci/app/homarr) ![Working status](https://ci-apps.yunohost.org/ci/badges/homarr.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/homarr.maintain.svg)

[![Install Homarr with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homarr)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Homarr quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place.
It integrates with the services you use to display information on the homepage (E.g. Show upcoming Sonarr/Radarr releases).

### Features

- Integrates with services you use.
- Search the web directly from your homepage.
- Real-time status indicator for every service.
- Automatically finds icons while you type the name of a service.
- Widgets that can display all types of information.
- Very light-weight and fast.


**Shipped version:** 0.15.0~ynh1

**Demo:** https://homarr.ajnart.fr/fr

## Screenshots

![Screenshot of Homarr](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://homarr.dev/>
* Official user documentation: <https://homarr.dev/docs/about>
* Official admin documentation: <https://homarr.dev/docs/about>
* Upstream app code repository: <https://github.com/ajnart/homarr>
* YunoHost Store: <https://apps.yunohost.org/app/homarr>
* Report a bug: <https://github.com/YunoHost-Apps/homarr_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/homarr_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
or
sudo yunohost app upgrade homarr -u https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>