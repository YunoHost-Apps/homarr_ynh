<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Homarr per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/homarr.svg)](https://dash.yunohost.org/appci/app/homarr) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/homarr.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/homarr.maintain.svg)

[![Installa Homarr con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homarr)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Homarr su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place.
It integrates with the services you use to display information on the homepage (E.g. Show upcoming Sonarr/Radarr releases).

### Features

- Integrates with services you use.
- Search the web directly from your homepage.
- Real-time status indicator for every service.
- Automatically finds icons while you type the name of a service.
- Widgets that can display all types of information.
- Very light-weight and fast.


**Versione pubblicata:** 0.15.0~ynh1

**Prova:** <https://homarr.ajnart.fr/fr>

## Screenshot

![Screenshot di Homarr](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://homarr.dev/>
- Documentazione ufficiale per gli utenti: <https://homarr.dev/docs/about>
- Documentazione ufficiale per gli amministratori: <https://homarr.dev/docs/about>
- Repository upstream del codice dell’app: <https://github.com/ajnart/homarr>
- Store di YunoHost: <https://apps.yunohost.org/app/homarr>
- Segnala un problema: <https://github.com/YunoHost-Apps/homarr_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/homarr_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
o
sudo yunohost app upgrade homarr -u https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
