<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Homarr pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/homarr)](https://ci-apps.yunohost.org/ci/apps/homarr/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/homarr)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/homarr)

[![Installer Homarr avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homarr)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Homarr rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Homarr est une page d'accueil simple et légère pour votre serveur, qui vous aide à accéder facilement à tous vos services en un seul endroit.
Il s'intègre aux services que vous utilisez pour afficher des informations sur la page d'accueil (par exemple, afficher les prochaines versions de Sonarr/Radar).

### Caractéristiques

- S'intègre aux services que vous utilisez.
- Recherchez sur le Web directement depuis votre page d'accueil.
- Indicateur d'état en temps réel pour chaque service.
- Recherche automatiquement les icônes pendant que vous tapez le nom d'un service.
- Des widgets pouvant afficher tous types d'informations.


**Version incluse :** 0.15.10~ynh1

**Démo :** <https://homarr.ajnart.fr/fr>

## Captures d’écran

![Capture d’écran de Homarr](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://homarr.dev/>
- Documentation officielle utilisateur : <https://homarr.dev/docs/about>
- Documentation officielle de l’admin : <https://homarr.dev/docs/about>
- Dépôt de code officiel de l’app : <https://github.com/ajnart/homarr>
- YunoHost Store : <https://apps.yunohost.org/app/homarr>
- Signaler un bug : <https://github.com/YunoHost-Apps/homarr_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/homarr_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
ou
sudo yunohost app upgrade homarr -u https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
