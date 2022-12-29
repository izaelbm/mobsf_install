#Requirements MOBSF
https://mobsf.github.io/docs/#/requirements

STEP 1
#Add source repository in /etc/apt/sources.list.
deb http://security.debian.org/debian-security buster/updates main

STEP 2
#Install django
https://docs.djangoproject.com/en/4.1/topics/install/
$git clone https://github.com/django/django.git
$python -m pip install -e django/

STEP 3
in kali execute this command.
#sudo apt install python3-dev python3-venv python3-pip build-essential libffi-dev libssl-dev libxml2-dev libxslt1-dev libjpeg8-dev zlib1g-dev wkhtmltopdf

STEP 4
#Download and install Mobsf
$git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF.git
$cd Mobile-Security-Framework-MobSF
$./setup.sh

se der erro
**** Change code (manage.py) => FROM python -m venv venv TO python -m venv venv --without-pip ******

STEP 5
#in the root directory run this commans.
$virtualenv -p python3 venv
$source venv/bin/activate
$pip install -r requirements.txt
$python manage.py runserver
$./run.sh 127.0.0.1:8000
