

# Introduction

This project is created for SEN4015 course

The project is written with django 4.0.1 and python 3.8 in mind.


### Main features

* Admin Panal

* Custom Login and Registraion

* ability to add movies to a Watchlist

      
    

# Getting Started

First clone the repository from Github and switch to the new directory:

    $ git clone https://github.com/aameralkazemi/SEN4015-Project
    $ cd SEN4015-Project
    
First Install virtualenv 

    $ pip3 -m venv venv
    
Activate the virtualenv for your project.

    $ source venv/bin/activate
    
Install project dependencies:

    $ pip install -r src/requirements.txt
    
    
Then simply apply the migrations:

    $ python manage.py migrate
    

You can now run the development server:

    $ python manage.py runserver
