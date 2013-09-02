## Todo Application##

A simple todo application built using Python 2.7 , Flask , SQLAlchemy , PostgreSQL 9.2 , and Twitter Bootstrap.

1. Create the application using 
```
$ rhc app create todo python-2.7 postgresql-9.2
```

2. Pull the source code from github
```
$ git remote add upstream -m master https://github.com/shekhargulati/todo-flask-openshift-quickstart.git
$ git pull -s recursive -X theirs upstream master
```

3. Push the application to OpenShift
```
$ git push
```
