<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# FilePizza YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/filepizza)](https://ci-apps.yunohost.org/ci/apps/filepizza/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/filepizza)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/filepizza)

[![Instalatu FilePizza YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filepizza)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek FilePizza YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Using WebRTC, FilePizza eliminates the initial upload step required by other web-based file sharing services. When senders initialize a transfer, they receive a "tempalink" they can distribute to recipients. Upon visiting this link, recipients' browsers connect directly to the sender’s browser and may begin downloading the selected file. Because data is never stored in an intermediary server, the transfer is fast, private, and secure.

**Paketatutako bertsioa:** 2.0.0~ynh1

**Demoa:** <https://file.pizza/>

## Pantaila-argazkiak

![FilePizza(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://file.pizza/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/kern/filepizza>
- YunoHost Denda: <https://apps.yunohost.org/app/filepizza>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/filepizza_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
edo
sudo yunohost app upgrade filepizza -u https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
