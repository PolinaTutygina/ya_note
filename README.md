Инструкция по проекту
1. Склонируйте проект YaNews из репозитория: git clone …
2. Создайте виртуальное окружение python -m venv venv
3. Запустите виртуальное окружение и установите зависимости из файла requirements.txt: pip install -r requirements.txt
4. Миграции уже созданы, выполните их: python manage.py migrate.
5. Cоздайте суперпользователя: python manage.py createsuperuser.
6. Запустите проект: python manage.py runserver