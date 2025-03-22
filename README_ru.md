<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Homarr для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/homarr)](https://ci-apps.yunohost.org/ci/apps/homarr/)
![Состояние работы](https://apps.yunohost.org/badge/state/homarr)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/homarr)

[![Установите Homarr с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homarr)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Homarr быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place.
It integrates with the services you use to display information on the homepage (E.g. Show upcoming Sonarr/Radarr releases).

### Features

- Integrates with services you use.
- Search the web directly from your homepage.
- Real-time status indicator for every service.
- Automatically finds icons while you type the name of a service.
- Widgets that can display all types of information.
- Very light-weight and fast.


**Поставляемая версия:** 1.12.0~ynh1

**Демо-версия:** <https://homarr.ajnart.fr/fr>

## Снимки экрана

![Снимок экрана Homarr](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://homarr.dev/>
- Официальная документация пользователя: <https://homarr.dev/docs/about>
- Официальная документация администратора: <https://homarr.dev/docs/about>
- Репозиторий кода главной ветки приложения: <https://github.com/homarr-labs/homarr>
- Магазин YunoHost: <https://apps.yunohost.org/app/homarr>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/homarr_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/homarr_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
или
sudo yunohost app upgrade homarr -u https://github.com/YunoHost-Apps/homarr_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
