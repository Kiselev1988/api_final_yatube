# Проект API Yatube

## API для социальной сети "Yatube".

API позволяет добавлять новых пользователей, создавать,
редактировать, удалять посты, писать комментарии и подписываться на авторов публикаций.


### Установка:

Клонировать репозиторий и перейти в его директорию:

```
git clone https://github.com/Kiselev1988/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
pythons manage.py runserver
```

## Документация к API:

```
http://127.0.0.1:8000/redoc/
```

Регистрация нового пользователя:

```
http://127.0.0.1:8000/api/v1/users/
```