<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Homarr YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/homarr)](https://ci-apps.yunohost.org/ci/apps/homarr/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/homarr)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/homarr)

[![Instalatu Homarr YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homarr)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Homarr YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place.
It integrates with the services you use to display information on the homepage (E.g. Show upcoming Sonarr/Radarr releases).

### Features

- Integrates with services you use.
- Search the web directly from your homepage.
- Real-time status indicator for every service.
- Automatically finds icons while you type the name of a service.
- Widgets that can display all types of information.
- Very light-weight and fast.


**Paketatutako bertsioa:** 1.13.1~ynh1

**Demoa:** <https://homarr.ajnart.fr/fr>

## Pantaila-argazkiak

![Homarr(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://homarr.dev/>
- Erabiltzaileen dokumentazio ofiziala: <https://homarr.dev/docs/about>
- Administratzaileen dokumentazio ofiziala: <https://homarr.dev/docs/about>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/homarr-labs/homarr>
- YunoHost Denda: <https://apps.yunohost.org/app/homarr>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/homarr_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/homarr_ynh/tree/testing).

`testing` abarra probatzeko, honakoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
edo
sudo yunohost app upgrade homarr -u https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
