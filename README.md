# Inanutshell
 store.listen.learn

inanutshell1 is a django package with templates, models, views and forms AND NEED TO UPDATE API KEYS AND MONGODB SRV

First you need to install virtual enviroment and then libraries from requirements


LINUX

$ virtualenv <env_name>

$ source <env_name>/bin/activate

$ (<env_name>)$ pip install -r path/to/requirements.txt


WINDOWS

$ virtualenv <env_name>

$ zappaenv1\\Scripts\\activate.bat

$ (<env_name>)$ pip install -r path/to/requirements.txt


DJANGO COMMANDS TO MAKE ANY CHANGES

$ conda activate MyDjangoEnv

$ python manage.py makemigrations

$ python manage.py migrate

$ python manage.py runserver 


TO UPDATE STATIC FILES TO LAMBDA

$ python manage.py collectstatic --no-input

TO RUN ZAPPA 

$ zappa update dev

AWS lamda and Alexa files are also provides in zip



