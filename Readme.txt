mkdir tinyurlproject

cd tinyurlproject

virtualenv venv -p python3.6

source venv/bin/activate

pip install Django==2.1.*

django-admin startproject tinyurlproject

python manage.py runserver

Emmet For Faster HTML & CSS Workflow

Emmet installation:

Installation

    Go to Help > Install New Software… in your Eclipse IDE
    Add http://download.emmet.io/eclipse/updates/ in update sites
    Check Emmet for Eclipse group in available plugins list, click Next button and follow the installation instructions
    Restart Eclipse

Emmet Overview

This plugin provides the features:

    Expand abbreviations by Tab key
    Tab stops and linked mode support
    Simple install and update process
    Change action shortcuts in Eclipse’s Keys preferences page
    Works across all Eclipse editors
    Preferences support to fine-tune output for each syntax and add new abbreviations and snippets
    
python manage.py migrate

python manage.py makemigrations
    
python manage.py createsuperuser
    
    sudo fuser -k 8000/tcp. This should kill all the processes associated with port 8000.
    
    or netstat -nlpt
    
    (trydjango) [preeti@oc1238606604 src]$ python manage.py

Type 'manage.py help <subcommand>' for help on a specific subcommand.

Available subcommands:

[auth]
    changepassword
    createsuperuser

[contenttypes]
    remove_stale_contenttypes

[django]
    check
    compilemessages
    createcachetable
    dbshell
    diffsettings
    dumpdata
    flush
    inspectdb
    loaddata
    makemessages
    makemigrations
    migrate
    sendtestemail
    shell
    showmigrations
    sqlflush
    sqlmigrate
    sqlsequencereset
    squashmigrations
    startapp
    startproject
    test
    testserver

[sessions]
    clearsessions

[staticfiles]
    collectstatic
    findstatic
    runserver
    
Queryset django:
(trydjango) [preeti@oc1238606604 src]$ python manage.py shell
Python 3.6.8 (default, Jun 11 2019, 15:15:01) 
[GCC 4.8.5 20150623 (Red Hat 4.8.5-39)] on linux
Type "help", "copyright", "credits" or "license" for more information.
(InteractiveConsole)
>>> from posts.models import Post
>>> Post.objects.all()
<QuerySet [<Post: Try Django 2.1>, <Post: Bootstrap learn>, <Post: learn javascript new>]>
>>> Post.objects.filter(title='javascript')
<QuerySet []>
>>> Post.objects.filter(title='javascript')
<QuerySet []>
>>> Post.objects.filter(title__icontains='javascript')
<QuerySet [<Post: learn javascript new>]>
>>> 



