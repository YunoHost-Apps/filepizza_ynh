<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# FilePizza untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/filepizza)](https://ci-apps.yunohost.org/ci/apps/filepizza/)
![Status kerja](https://apps.yunohost.org/badge/state/filepizza)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/filepizza)

[![Pasang FilePizza dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filepizza)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang FilePizza secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Using WebRTC, FilePizza eliminates the initial upload step required by other web-based file sharing services. When senders initialize a transfer, they receive a "tempalink" they can distribute to recipients. Upon visiting this link, recipients' browsers connect directly to the sender’s browser and may begin downloading the selected file. Because data is never stored in an intermediary server, the transfer is fast, private, and secure.

**Versi terkirim:** 2025.02.02~ynh1

**Demo:** <https://file.pizza/>

## Tangkapan Layar

![Tangkapan Layar pada FilePizza](./doc/screenshots/screenshot.png)

## :red_circle: Antifitur

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://file.pizza/>
- Depot kode aplikasi hulu: <https://github.com/kern/filepizza>
- Gudang YunoHost: <https://apps.yunohost.org/app/filepizza>
- Laporkan bug: <https://github.com/YunoHost-Apps/filepizza_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
atau
sudo yunohost app upgrade filepizza -u https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
