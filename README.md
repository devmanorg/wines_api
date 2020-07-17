# API винного магазина

в распоряжении только одна GET-ручка: `/api/wine_list`, выдаёт список вин из базы данных в формате JSON.

## Запуск

Для запуска сайта вам понадобится Python третьей версии.

Скачайте код с GitHub. Установите зависимости:

```sh
pip install -r requirements.txt
```

Создайте базу данных SQLite

```sh
python3 manage.py migrate
```

Запустите разработческий сервер

```
python3 manage.py runserver
```
