run:
    python manage.py runserver

test:
    python manage.py test


#Static analysis tools

LINTERS = pylint flake8   

FORMATTERS = black