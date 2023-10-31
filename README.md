<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# FilePizza for YunoHost

[![Integration level](https://dash.yunohost.org/integration/filepizza.svg)](https://dash.yunohost.org/appci/app/filepizza) ![Working status](https://ci-apps.yunohost.org/ci/badges/filepizza.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/filepizza.maintain.svg)

[![Install FilePizza with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filepizza)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install FilePizza quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Using WebRTC, FilePizza eliminates the initial upload step required by other web-based file sharing services. When senders initialize a transfer, they receive a "tempalink" they can distribute to recipients. Upon visiting this link, recipients' browsers connect directly to the sender’s browser and may begin downloading the selected file. Because data is never stored in an intermediary server, the transfer is fast, private, and secure.

**Shipped version:** 1.1.0~ynh5

**Demo:** https://file.pizza/

## Screenshots

![Screenshot of FilePizza](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://file.pizza/>
* Upstream app code repository: <https://github.com/kern/filepizza>
* YunoHost Store: <https://apps.yunohost.org/app/filepizza>
* Report a bug: <https://github.com/YunoHost-Apps/filepizza_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
or
sudo yunohost app upgrade filepizza -u https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
