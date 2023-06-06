# :space_invader: MTD
MTD (MyTestDownloader) — Скрипт, написанный на Python, созданный для получения ответов MyTestX

## 	:question: Как пользоваться
1) Задайте все настройки через файл `config.ini`
2) Запустите `main.exe` и подождите
3) Если настройки были указаны верно, то через несколько секунд откроется окно редактора с заданиями и ответами на них

## :toolbox: О конфиге
*config.ini*:
```
[SETTINGS]
SERVER_IP = 127.0.0.1
SERVER_PORT = 7777
CLIENT_NAME = User
```

- **SERVER_IP** — Название (или IP) компьютера-сервера
- **SERVER_PORT** — Порт компьютера-сервера

  *(Эти два параметра можно узнать из настроек MyTestStudent)*
- **CLIENT_NAME** — Имя клиента (можно задать любого, этот параметр отображается только в логах сервера)

