Django Startup
==============

A simple shell script to bootstrap Django project.

Quickstart
==============
First, download `setup.sh`. Then run the following command:
```
$ ./setup.sh
```
By default `Django Startup` wil create a project name `demo`.
```
$ ./setup.sh
.....
.....
.....
$ ls -p
demo_project/  env-demo/  setup.sh
```
The `demo_project` contains all project files, it is same structure like when you run official Django command `django-admin.py startproject demo_project`.

The `env-demo` is a Python virtual environment, same like when you run `virtualenv env-demo`

If you wish to change the project name, you can pass a new name as a first parameter to setup.py. An example, if you like to use a project name 'camp':
```
$ ./setup.sh camp
.....
.....
.....
$ ls -p
camp_project/  env-camp/  setup.sh
```
