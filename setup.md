To install:
Vagrant initialise - intialises project as Vagrant project
`vagrant init`

base image is ubuntu
`config.vm.box = "base"`

`exit`
to reconnect
`vagrant up` to start the server

`vagrant ssh`

`ls -a` to view all files including invisible ones

set up virtual environment:
`mkvirtualenv profiles_api --python=python3`

close env
`deactivate`
open env
`workon profiles_api`

install packages using python package manager
`pip install Django==1.11`
`pip install djangorestframework==3.6.2`

src folder - source code
django project made of a series of app
src/profiles_project the root directory
another directory will the same name as the project

to see which python packages are already intalled
`pip freeze`
`pip freeze > requirements.txt`


test with djnago development server
http://127.0.0.1:1234/