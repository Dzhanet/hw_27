# Создание fixture и загрузка данных

Зайти в папку "ads/datasets" (там лежат файлы csv с данными)

Выполнить 'python3 load_csv_to_json.py' (получает данные из файлов csv, преобразует в json и помещает в папку с fixtures)

Необходимо создать миграцию "./manage.py makemigrations"  и накатить миграцию "./manage.py migrate"

Вернитесь в папку проекта и загрузите данные в БД выполните «python3 manage.py loaddata ads.json».
Выполнить «python3 manage.py loaddata categories.json»

# Доступные маршруты и методы

1) /ad/ - GET, POST
2) /ad/3 - GET
3) /cat/ - GET, POST
4) /cat/3/ - GET
