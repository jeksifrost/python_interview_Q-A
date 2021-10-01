mkdir firstproject


cd firstproject


python -m venv venv


Перетянуть файл activate.bat в командную строку и выполнить его (либо по пути venv\scripts\activate)


pip install django


django-admin startproject firstproject


__init__.py - обозначение того, что папка является пакетом


asgi.py, wsgi.py (Web Server Gateway Interface, Asynchronous Server Gateway Interface - Интерфейс шлюза веб-сервера, Интерйефс асинхронного серверного шлюза)
Отвечают за взаимодействие приложение с веб сервером


settings.py - файл настрое конфигурации


urls.py - файл со списком URL


чтобы Pycharm указать путь к venv: File -> Settings -> Project: firstproject -> Project Interpreter -> Шестеренка -> Add -> Existing Environment -> Три точки -> указать путь ..\venv\Scripts\python.exe -> Ok Ok Ok
Проверить в терминале Pycharm что venv активировано


python manage.py runserver


python manage.py migrate


python manage.py createsuperuser


можно переименовать папку проекта через refactor - rename в папку config


Создание приложения
python manage.py startapp APP_NAME


apps.py - фалй конфигурации приложения


admin.py - папка для добавления приложения в админку


models.py - файл для моделей ORM (Object-Relational Mapper - Объектно-ориентированное отображение) - тенология программирования, которая связывает базы данных с концепциями объектно-ориентированных языков программирования, создавая "виртуальную объектную базу данных"





