## Проект шаблон, для сборки flutter приложения для VKMiniApps.

### fl_app - flutter приложение (отгружается веб сервером).
### Описание внутри папки.

### npm - проект с npm пакетами vk-tunnel и http-server.
### Описание внутри папки.

### Шаги по сборке.
#### Собрать Flutter проект.
[Описание](./fl_app/readme.md)
### Подготовить сервер
[Описание](./npm/readme.md)
#### 2. Запустить локальный http-server.
#### 3. Запустить vk-tunnel.

### Ссылки
https://dev.vk.com/mini-apps/getting-started
https://dev.vk.com/mini-apps/bridge
https://dev.vk.com/libraries/tunnel

### Для работы нужны установленные npm и flutter_sdk
https://docs.npmjs.com/downloading-and-installing-node-js-and-npm
https://docs.flutter.dev/get-started/install

### Для удобства
### 1. Сборка flutter проекта и запуск локального http сервера.
### Вызывать заново, после изменений в коде. (пока так)
```shell
./build.sh
```
### 2. Можно не перезапускать. (локальный сервер становится публичным)
```shell
./vk-tunnel.sh
```
