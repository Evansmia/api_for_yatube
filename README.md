<h1>API для Yatube</h1>
<h2>Краткое описание</h2>
<li>Аутентификация по JWT-токену</li>
<li>Работа со списком всех публикаций блога и отдельными постами по id</li>
<li>Работа со списком всех комментариев и комментариев для публикации по id </li>
<li>Работа с подписчиками</li>
<li>Работа с группами</li>

## Как запустить проект

### Клонировать репозиторий
```git clone https://github.com/Evansmia/api_final_yatube.git```
### Создать и активировать виртуальное окружение
```
python3 -m venv venv<br>
source venv/Scripts/activate  #для Windows
source venv/bin/activate      #для Linux и macOS
```
### Установить зависимости из файла requirements.txt
```
pip install -r requirements.txt
```
### Выполнить миграции
```
python3 manage.py migrate
```
### Запустить проект
```
python manage.py runserver
```

### Приложение доступно по адресу: http://127.0.0.1:8000/
### Документация API: http://127.0.0.1:8000/redoc/