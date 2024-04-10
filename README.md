# Описание проекта:
## Проект api_yatube - это API социальной сети yatube.

```bash
cd api_final_yatube
```

## Cоздать и активировать виртуальное окружение:

```bash
python3 -m venv venv
source venv/bin/activate
```

## Установить зависимости из файла requirements.txt:

```bash
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

## Выполнить миграции:

```bash
python3 manage.py migrate
```

## Запустить проект:

```bash
python3 manage.py runserver
```

## Примеры запросов к API:
### Примеры запросов можно посмотреть по следующему адресу:

```bash
http://127.0.0.1:8000/redoc/
```
