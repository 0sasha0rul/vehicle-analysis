# vehicles-analysis
[![Python package](https://github.com/sweeteri/vehicle-analysis/actions/workflows/python-package.yml/badge.svg?branch=main)](https://github.com/sweeteri/vehicle-analysis/actions/workflows/python-package.yml)
### Технологии
- Python 3.12
- Django 5.2

### Запуск проекта в dev-режиме
- Установите и активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
``` 
- В корневой папке проекта создайте файл .env
- Пропишите в этом файле следующие переменные:
```
SECRET_KEY=some_key
DEBUG=True
``` 
- В папке с файлом manage.py выполните одну из команд:
```
python3 manage.py runserver
```
```
python manage.py runserver
```
### Приложения 
1) **calculator**
отвечает за расчеты эффективности, выбросов и энергопотребления
2) **vehicles**
содержит в себе модели машин и основные методы