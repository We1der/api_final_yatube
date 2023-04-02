# Yatube API
## API для проекта Yatude
Учебный проект для изучения django rest framework* 

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
```
pip install -r requirements.txt
``` 
- In the folder with the manage.py file, run the comman :
```
python3 manage.py runserver
```

### Примеры запросов:
GET запрос на получение списка постов:
```
http://127.0.0.1:8000/api/v1/posts/
```
GET запрос на получение конкретного поста:
```
http://127.0.0.1:8000/api/v1/posts/{id}/
```
### Author
Mikhail Frolov