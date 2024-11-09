<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Homarr untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/homarr.svg)](https://ci-apps.yunohost.org/ci/apps/homarr/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/homarr.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/homarr.maintain.svg)

[![Pasang Homarr dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homarr)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Homarr secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place.
It integrates with the services you use to display information on the homepage (E.g. Show upcoming Sonarr/Radarr releases).

### Features

- Integrates with services you use.
- Search the web directly from your homepage.
- Real-time status indicator for every service.
- Automatically finds icons while you type the name of a service.
- Widgets that can display all types of information.
- Very light-weight and fast.


**Versi terkirim:** 0.15.7~ynh1

**Demo:** <https://homarr.ajnart.fr/fr>

## Tangkapan Layar

![Tangkapan Layar pada Homarr](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://homarr.dev/>
- Dokumentasi pengguna resmi: <https://homarr.dev/docs/about>
- Dokumentasi admin resmi: <https://homarr.dev/docs/about>
- Depot kode aplikasi hulu: <https://github.com/ajnart/homarr>
- Gudang YunoHost: <https://apps.yunohost.org/app/homarr>
- Laporkan bug: <https://github.com/YunoHost-Apps/homarr_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/homarr_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
atau
sudo yunohost app upgrade homarr -u https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
