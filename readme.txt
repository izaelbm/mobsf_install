Requirements -> https://mobsf.github.io/docs/#/requirements

Add source repository in /etc/apt/sources.list.
deb http://security.debian.org/debian-security buster/updates main

in kali execute this command.
#sudo apt install python3-dev python3-venv python3-pip build-essential libffi-dev libssl-dev libxml2-dev libxslt1-dev libjpeg8-dev zlib1g-dev wkhtmltopdf

in the root directory run this commans.
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py runserver
