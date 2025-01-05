<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# FilePizza для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/filepizza)](https://ci-apps.yunohost.org/ci/apps/filepizza/)
![Состояние работы](https://apps.yunohost.org/badge/state/filepizza)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/filepizza)

[![Установите FilePizza с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filepizza)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить FilePizza быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Using WebRTC, FilePizza eliminates the initial upload step required by other web-based file sharing services. When senders initialize a transfer, they receive a "tempalink" they can distribute to recipients. Upon visiting this link, recipients' browsers connect directly to the sender’s browser and may begin downloading the selected file. Because data is never stored in an intermediary server, the transfer is fast, private, and secure.

**Поставляемая версия:** 2025.01.05~ynh1

**Демо-версия:** <https://file.pizza/>

## Снимки экрана

![Снимок экрана FilePizza](./doc/screenshots/screenshot.png)

## :red_circle: Анти-функции

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://file.pizza/>
- Репозиторий кода главной ветки приложения: <https://github.com/kern/filepizza>
- Магазин YunoHost: <https://apps.yunohost.org/app/filepizza>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/filepizza_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
или
sudo yunohost app upgrade filepizza -u https://github.com/YunoHost-Apps/filepizza_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
