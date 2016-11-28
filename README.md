# Fireh Runner Demo

## How to

1. run git submodule update --init --recursive
2. run ./configure.sh
3. run ./runner pip install django
4. run ./runner pip install uwsgi
5. run ./runner django-admin startproject blog
6. run ./runner django-manage startapp blogposting
7. run ./runner uwsgi-run
