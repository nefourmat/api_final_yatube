##  Описание проекта:


## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
```sh
git clone https://github.com/nefourmat/api_final_yatube.git
```
Cоздать и активировать виртуальное окружение:
```sh
python -m venv venv
```
```sh
source venv/bin/activate
```
Установить зависимости из файла requirements.txt:
```sh
pip install -r requirements.txt
```
Выполнить миграции:
```sh
python3 manage.py migrate
```
Запустить проект:
```sh
python3 manage.py runserver
```

Примеры запросов к API:

| Метод | Пример |
| ------ | ------ |
| Получить список всех постов (GET): | /api/v1/posts/|
| Получить определенный пост (GET): | /api/v1/posts/1/ |
| Получить коментарии определенного поста (GET): | /api/v1/posts/1/comments/ |
| Получить список всех групп (GET): | /api/v1/groups/ |
| Создать новый пост (POST). Требуется аутентификация | /api/v1/posts/ |

