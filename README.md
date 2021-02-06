hello 
i am using gitbash to in setting up a django project
open terminal
   $ mkdir /c/simpleblog 
   $cd /c/simpleblog

create virtual environment
   $python -mvenv virt
turn on environment on windows
   $source virt/Scripts/activate

then install django
   $ pip install django

name the project
   $django-admin.py startproject mysite
directory
   $ls    (manage.py) then you are on the right side
then,
   $python manage.py migrate 

then 
    $python manage.py runserver

create super user
    $winpty python manage.py createsuperuser
