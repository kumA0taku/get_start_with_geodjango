###first###
`pip install virtualenv`

###2###
`virtualenv lifeingis`

###3###
`source activate >> cd lifeingis OR cd lifeingis/Scripts> activate`

###4###
`pip freeze`

###5###
`pip install django`

###6###
`pip freeze >> cd ..`

###7###
`django-admin startproject agricom`

###8###
`cd agricom >> python manage.py startapp reporter`

###9###
`python manage.py migrate >> python manage.py runserver`

###10###
`python manage.py createsuperuser #save username & pass`

###11###
`python manage.py makemigrations >> python manage.py migrate >> python manage.py runserver`
