I have tried to encooperate most of the things that were required in the assignment in this project.
 
IMPORTANT : You need to create a database in Psql in your local first and then give the details of the same in the settings.py file(under the symb_assignment folder) alongwith name and passoword if any, after that you need to migrate the database and you are good to go with the working of the APIs.

For running this you just need to install python, django, django_extensions and PyJwt in your environment and you are good to go with this. Just make sure after installing the enviroment you migrate the db(python manage.py migrate) and then run the manage.py(python manage.py runserver) file accordingly.

use following after you have installed the environment(required for the project) from the terminal:

 python manage.py makemigrations
 python manage.py migrate
 python manage.py runserver


Under url.py in contact_app folder, you can look at the api urls that are there.

