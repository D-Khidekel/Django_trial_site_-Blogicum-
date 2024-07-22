# Blogicum

Создание или активация виртуального окружения:
1. Создание: python -m venv venv
2. Активация: source venv/Scripts/activate

Чтобы установить все пакеты из файла requirements.txt, можно использовать команду:
pip install -r requirements.txt

Команда для обновления пакетного менеджера:
python.exe -m pip install --upgrade pip

Команда для выполнения миграций:
python manage.py migrate


Запуск сервера:
Сперва ужно перейти в каталог с файлом manage.py:
    cd blogicum

Затем выполнить команду:
    python manage.py runserver

После этого перейти в браузере по адресу:
    http://127.0.0.1:8000/
