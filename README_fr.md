<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# FilePizza pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/filepizza)](https://ci-apps.yunohost.org/ci/apps/filepizza/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/filepizza)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/filepizza)

[![Installer FilePizza avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filepizza)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer FilePizza rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Grâce à WebRTC, FilePizza élimine l'étape initiale de téléchargement requise par d'autres services de partage de fichiers basés sur le web. Lorsque les expéditeurs initialisent un transfert, ils reçoivent un « tempalink » qu'ils peuvent distribuer aux destinataires. En visitant ce lien, les navigateurs des destinataires se connectent directement au navigateur de l'expéditeur et peuvent commencer à télécharger le fichier sélectionné. Les données n'étant jamais stockées sur un serveur intermédiaire, le transfert est rapide, privé et sécurisé.

**Version incluse :** 2.0.0~ynh1

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
