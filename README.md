![SHAME](https://travis-ci.org/UrLab/incubator.svg?branch=master)
# incubator
Let's bootstrap an new incubator for UrLab ! (in python and with an API this time)

Rapide brainstorming https://pad.lqdn.fr/p/incubator

# Install dependencies (Ubuntu)

    (Ubuntu) sudo apt-get install python3-dev python3-setuptools libtiff4-dev libjpeg8-dev zlib1g-dev libfreetype6-dev liblcms2-dev libwebp-dev tcl8.5-dev tk8.5-dev
    (Fedora) sudo dnf install libtiff-devel libjpeg-devel libzip-devel freetype-devel lcms2-devel libwebp-devel tcl-devel tk-devel python3-devel python3-setuptools

# Setup

    pyvenv-3.4 ve # or virtualenv-3.4
    source ve/bin/activate
    pip install -r requirements.txt
    ./manage.py migrate
    ./manage.py runserver

# Create a user

    ./manage.py createsuperuser
    
