
# Exemple de Django amb OAuth2

Extret de la web oficial del plugin django-oauth-toolkit

    https://django-oauth-toolkit.readthedocs.io/en/latest/tutorial/tutorial_01.html

Abans de començar convé mirar-se a fons el sistema d'autenticació de Django 1.11:

    https://docs.djangoproject.com/en/dev/topics/auth/default/#django.contrib.auth.views.login
    https://docs.djangoproject.com/en/1.11/topics/auth/

## Instal·lació

...

## Standard auth

Primer convé familiaritzar-se amb la auth estàndard. No cal cap paquet addicional.

1. Afegir les auth views a urls.py de la site (n'afegeix diverses amb un sol include)
    https://docs.djangoproject.com/en/dev/topics/auth/default/#module-django.contrib.auth.views
2. Afegir templates base.html i registration/login.html a:
	/app1/templates
3. Crea BD (migrate) i un superuser
4. Arrenca i comprova les auth views mirant http://localhost:8000 i executant abans
    $ python manage runserver

