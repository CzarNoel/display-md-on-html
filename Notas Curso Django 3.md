# FLUXOGRAMA FUNCIONAMENTO BÁSICO
   > 1.urls

   > 2.views

   > 3.templates -> pasta interna

   > 4.arquivo html

# CONSIDERAR A ESTRUTURA

 O *projeto* é o próprio *website*.
 
 Dentro de cada *projeto* temos vários *apps* que rodam dentro do mesmo.

 Portanto: Projeto (website) > Apps


# CRIANDO PROJETO
 ~~~ 
 django-admin startproject projectname
 ~~~

# CRIANDO APP
 Criar app no diretório do projeto 
 ~~~
 python3 manage.py startapp appname
 ~~~

 ## APÓS CRIAR O APP
 >1. Add ao settings.py o **app** criado
 ~~~~
 INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'app criado',
]
~~~~
> 2. Add ao urls.py o **PATH**


