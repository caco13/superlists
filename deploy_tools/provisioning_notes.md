Provisioning a new site
=======================

## Required packages:

* nginx
* Python 3.6
* virtualenv + pip
* Git

eg, on Ubuntu:

    sudo add-apt-repository ppa:fkrull/deadsnakes
    sudo apt install nginx git python3.6 python3.6-venv

## Nginx virtual Host config

* see nginx.template.conf
* replace SITENAME with, e.g., staging.my-domain.com

## Folder structure:
Assume we have a user account at /home/username

/home/username
|_ stites
   |_ SITEMANE
      |- database
      |- source
      |- static
      |_ virtualenv
