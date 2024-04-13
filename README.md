git clone
--------------------------------------------
cd <>
--------------------------------------------
(option) # pip install virtualenv
---------------------------------------
(option) # virtualenv venv
--------------------------------------------------
python -m venv env
-----------------------------------------------
# Windows
.\env\Scripts\activate

# Linux and Mac
source env/bin/activate
----------------------------------------------
pip install django
-------------------------------------------------
pip install Pillow
--------------------------------------------------
pip install -r requirements.txt-
--------------------------------------------------
python.exe -m pip install --upgrade pip
------------------------------------------------------
python manage.py makemigrations
python manage.py migrate
----------------------------------------
python manage.py runserver
--------------------------------------------
# admin password change
python manage.py changepassword <admin name>
-----------------------------------------------
python manage.py createsuperuser
