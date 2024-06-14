<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# FilePizza per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/filepizza.svg)](https://dash.yunohost.org/appci/app/filepizza) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/filepizza.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/filepizza.maintain.svg)

[![Installa FilePizza con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filepizza)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare FilePizza su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Using WebRTC, FilePizza eliminates the initial upload step required by other web-based file sharing services. When senders initialize a transfer, they receive a "tempalink" they can distribute to recipients. Upon visiting this link, recipients' browsers connect directly to the sender’s browser and may begin downloading the selected file. Because data is never stored in an intermediary server, the transfer is fast, private, and secure.

**Versione pubblicata:** 1.1.0~ynh7

**Prova:** <https://file.pizza/>

## Screenshot

![Screenshot di FilePizza](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://file.pizza/>
- Repository upstream del codice dell’app: <https://github.com/kern/filepizza>
- Store di YunoHost: <https://apps.yunohost.org/app/filepizza>
- Segnala un problema: <https://github.com/YunoHost-Apps/filepizza_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
o
sudo yunohost app upgrade filepizza -u https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
