# instant.io for YunoHost

[![Integration level](https://dash.yunohost.org/integration/instant.svg)](https://dash.yunohost.org/appci/app/instant) ![](https://ci-apps.yunohost.org/ci/badges/instant.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/instant.maintain.svg)  
[![Install Etherpad-Lite with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=instant)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Etherpad-Lite quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

> :warning: This package installs Etherpad-Lite (without MyPads and plugins). It uses PostgreSQL as a database.
>If you want to install Etherpad with the MyPads plugin, use the [Etherpad MyPads package](https://github.com/YunoHost-Apps/etherpad_mypads_ynh).

## Overview
Etherpad allows you to edit documents collaboratively in real-time, much like a live multi-player editor that runs in your browser. Write articles, press releases, to-do lists, etc. together with your friends, fellow students or colleagues, all working on the same document at the same time.

**Shipped version:** 1.8.7

## Screenshots

![](https://etherpad.org/img/etherpad_demo.gif)

## Demo

* [Official demo](https://video.etherpad.com/)

## Configuration

You can access Etherpad's admin panel at `domain.tld/admin`. The configuration file for Etherpad is at the path `/var/www/etherpad/settings.json`.

*Skin Builder* (accessible at this address `domain.tld/pad/p/test#skinvariantsbuilder`) allows you to customize the skin of your pad. It will give you a parameter to copy into your configuration file `/var/www/etherpad/settings.json`.

## Documentation

 * Official documentation: http://etherpad.org/doc/v1.8.7
 * YunoHost documentation: https://yunohost.org/#/app_etherpad

## YunoHost specific features

#### Multi-users support

 * Is LDAP auth supported? **No**
 * Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![](https://ci-apps.yunohost.org/ci/logs/filepizza%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/etherpad/)
* ARMv8-A - [![](https://ci-apps-arm.yunohost.org/ci/logs/filepizza%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/etherpad/)

## Limitations

## Additionnal informations

## Links

 * Report a bug: https://github.com/YunoHost-Apps/instant_ynh/issues
 * Upstream app repository: https://github.com/kern/filepizza
 * YunoHost website: https://yunohost.org/

---

## Developers infos

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/instant_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/instant_ynh/tree/testing --debug
or
sudo yunohost app upgrade instant s-u https://github.com/YunoHost-Apps/instant_ynh/tree/testing --debug
```
