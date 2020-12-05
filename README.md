# Inanutshell
 store.listen.learn

inanutshell1 is a django package with templates, models, views and forms

First you need to install virtual enviroment and then libraries from requirements
linux
$ virtualenv <env_name>
$ source <env_name>/bin/activate
$ (<env_name>)$ pip install -r path/to/requirements.txt

windows
$ virtualenv <env_name>
$ zappaenv1\\Scripts\\activate.bat
$ (<env_name>)$ pip install -r path/to/requirements.txt

Django commands to make any changes
$ conda activate MyDjangoEnv
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py runserver 

To Update static files to lamda
$ python manage.py collectstatic --no-input

to run zappa 
$ zappa update dev

AWS lamda and Alexa files are also provides in zip



