<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Homarr voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/homarr)](https://ci-apps.yunohost.org/ci/apps/homarr/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/homarr)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/homarr)

[![Homarr met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homarr)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Homarr snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place.
It integrates with the services you use to display information on the homepage (E.g. Show upcoming Sonarr/Radarr releases).

### Features

- Integrates with services you use.
- Search the web directly from your homepage.
- Real-time status indicator for every service.
- Automatically finds icons while you type the name of a service.
- Widgets that can display all types of information.
- Very light-weight and fast.


**Geleverde versie:** 0.15.7~ynh2

**Demo:** <https://homarr.ajnart.fr/fr>

## Schermafdrukken

![Schermafdrukken van Homarr](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://homarr.dev/>
- Officiele gebruikersdocumentatie: <https://homarr.dev/docs/about>
- Officiele beheerdersdocumentatie: <https://homarr.dev/docs/about>
- Upstream app codedepot: <https://github.com/ajnart/homarr>
- YunoHost-store: <https://apps.yunohost.org/app/homarr>
- Meld een bug: <https://github.com/YunoHost-Apps/homarr_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/homarr_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
of
sudo yunohost app upgrade homarr -u https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
