# Django-проект Блогикум
## Версия 1
Блогикум - это проста социальная сеть, в которой будут размещены различные посты. Данный проект реализован с помощью фраймворка Django и разбит на 3 части. Каждая последующая часть будет усовершенствованием предыдущей. В самой первой части было сделано следующее:
* Зарегистрированы 2 приложения: pages - для работы со статическими страницами проекта и blog - где описывается логика работы с публикациями и будущими пользователями (в следующих версиях проекта)
* Описан маршрутизатор (urls.py) и написаны соответствующие view-функции
* Созданы html-шаблоныс django-тегами, которые интегрированы в проект. С помощью Django различные страницы собираются из кусочков html-заготовок, в которые вставляются нужные переменные.
* Подключена статика для работы стилей


### Установка проекта:
* Скачать репозиторий: git clone proj-name в рабочую папку
* Создать виртуальное окружение: python -m venv venvname
* Активировать виртуальное окружение: source venv/Scripts/activate
* Установить необходимые библиотеки: pip install -r requirements.txt
* Запустить сервер: python manage.py runserver

### Особенности проекта:
* В первой версии проекта отображается всего 3 поста, которые просто хранятся в словаре.
* В проекте присутствует большое количество автотестов.
* Проект состоит из 3х частей. В данном репозитории находится первая.

![GitHub top language](https://img.shields.io/github/languages/top/VilmenAbramian/blogicum-1)



Финальный проект 4го спринта курса Python разработчик плюс.
Изначальное имя: django_sprint1
 
