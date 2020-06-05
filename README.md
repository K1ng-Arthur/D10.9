#D10.9 Принципы организации Django-проектов

Требования к проекту указаны в файле "requirements.txt"

Для запуска использовать в консоли команду: "python manage.py runserver"

После запуска сервера, проект будет доступен по адресу http://127.0.0.1:8000/

Админка: http://127.0.0.1:8000/admin/

Логин:  admin
пароль: admin

В БД было занесено некоторое количество автомобилей разных производителей и марок с заполнеными годами выпуска, цветом и типом КПП.

В проэкте можно фильтровать каталог по годам выпуска, цвету, типу КПП, а также выполнять поиск по названию и производителю автомобиля

Фильтрация реализована с помощью Q-объектов