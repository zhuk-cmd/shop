Для установки:

Открыть терминал или консоль и перейти в нужную Вам директорию
Прописать команду git clone git@github.com:zhuk-cmd/shop.git



Прописать следующие команды:


python3 -m venv ДиректорияВиртуальногоОкружения
source ДиректорияВиртуальногоОкружения/bin/activate

pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate


Запустить сервер - python manage.py runserver

Не забудьте создать директорию media, куда будут сохраняться изображения для товара

