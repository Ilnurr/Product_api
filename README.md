# Тестовое задание: API для продуктов и работа с фронтендом 

## Описание 
Это тестовое задание представляет собой небольшое Django-приложение, состоящее из двух частей:
1. **API для работы с продуктами** — создание и получение списка продуктов.
2. **Фронтенд на HTML и JavaScript** — отправка данных на API и отображение продуктов на странице. 

### Технология 
![python](https://img.shields.io/badge/Python-100000?style=for-the-badge&logo=python&logoColor=white) ![django](https://img.shields.io/badge/django-100000?style=for-the-badge&logo=django&logoColor=white) ![django rest](https://img.shields.io/badge/django%20rest-100000?style=for-the-badge&logo=django&logoColor=white) ![sqlite](https://img.shields.io/badge/SQLite-100000?style=for-the-badge&logo=sqlite&logoColor=white) ![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) ![vscode](https://img.shields.io/badge/VSCode-100000?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

## Запуск проекта 
Клонировать репозиторий:

```
git clone git@github.com:Ilnurr/Product_api.git
```

Перейти в репозиторий:

```
 cd product_api
```

Создать виртуальное окружение:

```
python3 -m venv env
```

Активировать виртуальное окружение:

```
source env/bin/activate 
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
Сервер будет запущен по адресу http://127.0.0.1:8000/.

Перейдите по адресу http://127.0.0.1:8000/api/ для доступа к фронтенду.

