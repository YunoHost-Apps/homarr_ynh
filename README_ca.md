<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# Homarr per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/homarr)](https://ci-apps.yunohost.org/ci/apps/homarr/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/homarr)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/homarr)

[![Instal·la Homarr amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homarr)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar Homarr de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place.
It integrates with the services you use to display information on the homepage (E.g. Show upcoming Sonarr/Radarr releases).

### Features

- Integrates with services you use.
- Search the web directly from your homepage.
- Real-time status indicator for every service.
- Automatically finds icons while you type the name of a service.
- Widgets that can display all types of information.
- Very light-weight and fast.


**Versió inclosa:** 1.13.1~ynh1

**Demo:** <https://homarr.ajnart.fr/fr>

## Captures de pantalla

![Captures de pantalla de Homarr](./doc/screenshots/screenshot.png)

## Documentació i recursos

- Lloc web oficial de l'aplicació: <https://homarr.dev/>
- Documentació oficial per l'usuari: <https://homarr.dev/docs/about>
- Documentació oficial per l'administrador: <https://homarr.dev/docs/about>
- Repositori oficial del codi de l'aplicació: <https://github.com/homarr-labs/homarr>
- Botiga YunoHost: <https://apps.yunohost.org/app/homarr>
- Reportar un error: <https://github.com/YunoHost-Apps/homarr_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/homarr_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
o
sudo yunohost app upgrade homarr -u https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>
