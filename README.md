To launch the project : 

cd "repertoire ou se situe le projet"
python create_database.py python manage.py makemigrations
python manage.py migrate
python manage.py load_data
python manage.py runserver
