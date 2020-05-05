# 2048 for YunoHost

[![Integration level](https://dash.yunohost.org/integration/2048.svg)](https://dash.yunohost.org/appci/app/2048) ![](https://ci-apps.yunohost.org/ci/badges/2048.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/2048.maintain.svg)  
[![Install 2048 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=2048)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install 2048 quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

2048 game

## Screenshots

![](https://cloud.githubusercontent.com/assets/1175750/8614312/280e5dc2-26f1-11e5-9f1f-5891c3ca8b26.png" alt="Screenshot"/)

## Demo

* [Official demo](https://play2048.co/)

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/2048%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps2048/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/2048%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/2048/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/2048_ynh/issues
 * Upstream app repository: https://github.com/gabrielecirulli/2048
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/2048_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/2048_ynh/tree/testing --debug
or
sudo yunohost app upgrade 2048 -u https://github.com/YunoHost-Apps/2048_ynh/tree/testing --debug
```
