# 2048 pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/2048.svg)](https://dash.yunohost.org/appci/app/2048) ![](https://ci-apps.yunohost.org/ci/badges/2048.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/2048.maintain.svg)  
[![Install 2048 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=2048)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d’installer 2048 rapidement et simplement sur un serveur Yunohost.  
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Jeu 2048

## Captures d’écran

![](https://cloud.githubusercontent.com/assets/1175750/8614312/280e5dc2-26f1-11e5-9f1f-5891c3ca8b26.png" alt="Screenshot"/)

## Démo

* [Démo officielle](https://play2048.co/)

#### Architectures supportées

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/2048%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps2048/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/2048%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/2048/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/2048_ynh/issues
 * Dépôt de l’application principale : https://github.com/gabrielecirulli/2048
 * Site web YunoHost : https://yunohost.org/

---

Informations pour les développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/2048_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/2048_ynh/tree/testing --debug
or
sudo yunohost app upgrade 2048 -u https://github.com/YunoHost-Apps/2048_ynh/tree/testing --debug
```
