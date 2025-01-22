<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# FilePizza dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/filepizza)](https://ci-apps.yunohost.org/ci/apps/filepizza/)
![Status działania](https://apps.yunohost.org/badge/state/filepizza)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/filepizza)

[![Zainstaluj FilePizza z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filepizza)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację FilePizza na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Using WebRTC, FilePizza eliminates the initial upload step required by other web-based file sharing services. When senders initialize a transfer, they receive a "tempalink" they can distribute to recipients. Upon visiting this link, recipients' browsers connect directly to the sender’s browser and may begin downloading the selected file. Because data is never stored in an intermediary server, the transfer is fast, private, and secure.

**Dostarczona wersja:** 2.0.0~ynh1

**Demo:** <https://file.pizza/>

## Zrzuty ekranu

![Zrzut ekranu z FilePizza](./doc/screenshots/screenshot.png)

## :red_circle: Niepożądane funkcje

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://file.pizza/>
- Repozytorium z kodem źródłowym: <https://github.com/kern/filepizza>
- Sklep YunoHost: <https://apps.yunohost.org/app/filepizza>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/filepizza_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
lub
sudo yunohost app upgrade filepizza -u https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
