<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# FilePizza pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/filepizza.svg)](https://dash.yunohost.org/appci/app/filepizza) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/filepizza.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/filepizza.maintain.svg)

[![Installer FilePizza avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filepizza)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer FilePizza rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Using WebRTC, FilePizza eliminates the initial upload step required by other web-based file sharing services. When senders initialize a transfer, they receive a "tempalink" they can distribute to recipients. Upon visiting this link, recipients' browsers connect directly to the sender’s browser and may begin downloading the selected file. Because data is never stored in an intermediary server, the transfer is fast, private, and secure.

**Version incluse :** 1.1.0~ynh7

**Démo :** <https://file.pizza/>

## Captures d’écran

![Capture d’écran de FilePizza](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://file.pizza/>
- Dépôt de code officiel de l’app : <https://github.com/kern/filepizza>
- YunoHost Store : <https://apps.yunohost.org/app/filepizza>
- Signaler un bug : <https://github.com/YunoHost-Apps/filepizza_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
ou
sudo yunohost app upgrade filepizza -u https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
