# [Глава 9] Приложение

## 1. Индекс основных команд Linux для начинающих

| Номер | Название команды | Описание команды | Глава |
| :------: | :------------------ | :--------------------------- | :----------------------------------------: |
| `cmd-01` | `apt update` | Обновление списка пакетов | [Глава о удаленном подключении](./ch03-ssh.md) |
| `cmd-02` | `apt upgrade` | Обновление пакетов системы | [Глава о удаленном подключении](./ch03-ssh.md) |
| `cmd-03` | `nano` | Текстовый редактор | [Глава о безопасности](./ch04-security.md) |
| `cmd-04` | `systemctl restart` | Перезапуск сервиса | [Глава о безопасности](./ch04-security.md) |
| `cmd-05` | `adduser` | Добавление пользователя | [Глава о безопасности](./ch04-security.md) |
| `cmd-06` | `apt install` | Установка пакета | [Глава о безопасности](./ch04-security.md) |
| `cmd-07` | `visudo` | Редактор для настройки sudo | [Глава о безопасности](./ch04-security.md) |
| `cmd-08` | `sudo` | Выполнение команды от имени root | [Глава о безопасности](./ch04-security.md) |
| `cmd-09` | `chmod` | Изменение прав доступа к файлу/папке | [Глава о безопасности](./ch04-security.md) |
| `cmd-10` | `mkdir` | Создание папки | [Глава о создании сайта](./ch05-webpage.md) |
| `cmd-11` | `systemctl reload` | Перезагрузка конфигурации сервиса | [Глава о создании сайта](./ch05-webpage.md) |
| `cmd-12` | `wget` | Загрузка файла/страницы из сети | [Глава об управлении сертификатами](./ch06-certificates.md) |
| `cmd-13` | `acme.sh` | Управление сертификатами с помощью acme.sh | [Глава об управлении сертификатами](./ch06-certificates.md) |
| `cmd-14` | `rm` | Удаление файлов/папок | [Глава о Xray сервере](./ch07-xray-server.md) |
| `cmd-15` | `crontab -e` | Редактирование crontab текущего пользователя | [Глава о Xray сервере](./ch07-xray-server.md) |
| `cmd-16` | `touch` | Создание пустого файла | [Глава о Xray сервере](./ch07-xray-server.md) |
| `cmd-17` | `systemctl` | Базовые команды управления сервисами systemd | [Глава о Xray сервере](./ch07-xray-server.md) |
| `cmd-18` | `reboot` | Перезагрузка Linux | [Глава о Xray сервере](./ch07-xray-server.md) |

## 2. Индекс важных конфигурационных файлов Linux

| Номер | Расположение файла | Описание файла | Глава |
| :-------: | :-------------------------------------- | :----------------------------- | :----------------------------------------: |
| `conf-01` | `/etc/ssh/sshd_config` | Конфигурация SSH сервера | [Глава о удаленном подключении](./ch03-ssh.md) |
| `conf-02` | `/etc/nginx/nginx.conf` | Конфигурация Nginx | [Глава о создании сайта](./ch05-webpage.md) |
| `conf-03` | `/etc/apt/sources.list` | Список репозиториев APT | [Глава о Xray сервере](./ch07-xray-server.md) |
| `conf-04` | `/etc/apt/sources.list.d/vpsadmin.list` | Список пользовательских репозиториев APT | [Глава о Xray сервере](./ch07-xray-server.md) |
| `conf-05` | `crontab -e` | Crontab текущего пользователя | [Глава о Xray сервере](./ch07-xray-server.md) |
| `conf-06` | `/etc/sysctl.conf` | Настройки ядра Linux | [Глава о Xray сервере](./ch07-xray-server.md) |
| `conf-07` | `/etc/sysctl.d/vpsadmin.conf` | Пользовательские настройки ядра Linux | [Глава о Xray сервере](./ch07-xray-server.md) |

## 3. Индекс важных файлов Xray

| Номер | Расположение файла | Описание файла | Глава |
| :-------: | :----------------------------------- | :------------ | :----------------------------------------: |
| `xray-01` | `/usr/local/etc/xray/config.json` | Конфигурация Xray | [Глава о Xray сервере](./ch07-xray-server.md) |
| `xray-02` | `/home/vpsadmin/xray_cert/xray.cert` | TLS сертификат | [Глава о Xray сервере](./ch07-xray-server.md) |
| `xray-03` | `/home/vpsadmin/xray_cert/xray.key` | TLS ключ | [Глава о Xray сервере](./ch07-xray-server.md) |
| `xray-04` | `/home/vpsadmin/xray_log/access.log` | Лог доступа Xray | [Глава о Xray сервере](./ch07-xray-server.md) |
| `xray-05` | `/home/vpsadmin/xray_log/error.log` | Лог ошибок Xray | [Глава о Xray сервере](./ch07-xray-server.md) | 