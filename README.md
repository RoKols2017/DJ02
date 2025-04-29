# 🌐 Django Многостраничный Сайт

Проект представляет собой базовый сайт на Django с использованием шаблонов, подключаемого меню и подвала, оформленный с помощью Bootstrap 5.

## 🚀 Технологии

- ```Python 3.13````
- ```Django 5.2````
- ```Bootstrap 5````

## ⚙️ Установка

1. Клонируйте репозиторий:
   ```
   git clone https://github.com/your-username/multi-page-django-site.git
   cd multi-page-django-site
   ```

2. Создайте виртуальное окружение и активируйте его:
   ```
   python -m venv .venv
   source .venv/bin/activate        # Linux/macOS
   .venv\Scripts\activate           # Windows
   ```

3. Установите Django:
   ```
   pip install django
   ```

4. Примените миграции:
   ```
   python manage.py migrate
   ```

5. Запустите сервер:
   ```
   python manage.py runserver
   ```

## 📁 Структура проекта

```
movie_project/
├── main/
│   ├── templates/
│   │   └── main/
│   │       ├── layout.html
│   │       ├── _navbar.html
│   │       ├── _footer.html
│   │       ├── page1.html
│   │       ├── page2.html
│   │       ├── page3.html
│   │       └── page4.html
│   ├── views.py
│   ├── urls.py
│   └── ...
├── movie_project/
│   ├── settings.py
│   ├── urls.py
│   └── ...
└── manage.py
```

## 🌐 Маршруты

- ```/page1``` — Главная (Страница 1)
- ```/page2``` — Страница 2
- ```/page3``` — Страница 3
- ```/page4``` — Страница 4

## ✨ Особенности

- Подключаемое меню: ```{% include 'main/_navbar.html' %}````
- Подключаемый подвал: ```{% include 'main/_footer.html' %}````
- Общий шаблон: ```layout.html```` с Bootstrap
- Русский интерфейс 🇷🇺
- Чистая структура шаблонов

## 📄 Лицензия

Данный проект предназначен для учебных целей. Вы можете модифицировать его под любые задачи.
