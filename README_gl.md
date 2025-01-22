<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# FilePizza para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/filepizza)](https://ci-apps.yunohost.org/ci/apps/filepizza/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/filepizza)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/filepizza)

[![Instalar FilePizza con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filepizza)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar FilePizza de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Using WebRTC, FilePizza eliminates the initial upload step required by other web-based file sharing services. When senders initialize a transfer, they receive a "tempalink" they can distribute to recipients. Upon visiting this link, recipients' browsers connect directly to the sender’s browser and may begin downloading the selected file. Because data is never stored in an intermediary server, the transfer is fast, private, and secure.

**Versión proporcionada:** 2.0.0~ynh1

**Demo:** <https://file.pizza/>

## Capturas de pantalla

![Captura de pantalla de FilePizza](./doc/screenshots/screenshot.png)

## :red_circle: Debes considerar

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentación e recursos

- Web oficial da app: <https://file.pizza/>
- Repositorio de orixe do código: <https://github.com/kern/filepizza>
- Tenda YunoHost: <https://apps.yunohost.org/app/filepizza>
- Informar dun problema: <https://github.com/YunoHost-Apps/filepizza_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
ou
sudo yunohost app upgrade filepizza -u https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
