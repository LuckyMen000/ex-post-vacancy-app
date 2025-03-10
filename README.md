# Веб-приложение для управление вакансиями 

<p>Это фуллстак приложение на Django,которое позволяет управлять вакансиями</p>

### Запуск проекта 

```
python -m venv myenv
cd myenv
cd Scripts
acitvate
cd ../..
```

### Установка зависимостей 

```
pip install -r requirements.txt
```

### Выполните миграцию в БД

```
python manage.py makemigrations
python manage.py migrate
```

### Создание админки 

```
python manage.py createsuperuser
```

### Запуск проекта 

```
python manage.py runserver
```
