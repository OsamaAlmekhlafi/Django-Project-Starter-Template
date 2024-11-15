# Django-Project-Starter-Template
"""<br>
Author: Anthony C. Emmanuel<br>
Title: Django Project Starter Template<br>
Version: 1.0.0<br>
Language: Python 3.6<br>
Date: 07-12-2018<br>
License: 3-clause BSD<br>
"""

A Django Template for creating basic webapp with features such as Authentication System, User Profile, etc.
The Template can be used out of the box for any type of website/webapp
<h1> Screen Shots </h1>
<font align="center">
<ul>
  <img src="https://raw.githubusercontent.com/mymi14s/mymi14s.github.io/master/index.png" alt=""/>
  <br><img src="https://raw.githubusercontent.com/mymi14s/mymi14s.github.io/master/Login_without_social_button.png" width="250"/>
  <img src="https://raw.githubusercontent.com/mymi14s/mymi14s.github.io/master/login_with_social_button.png" width="250"/>
  <img src="https://raw.githubusercontent.com/mymi14s/mymi14s.github.io/master/Signup.png" width="250"/>
    <br><img src="https://raw.githubusercontent.com/mymi14s/mymi14s.github.io/master/admin.png"/>
</ul>
</font>

<h1>Language Requirement</h1>
  - Python 3.6 (Minimum >= 3.5)
  - Django 2.1.4 (Minimum >= 2.0)

<h1>Features</h1>

+ Authentication System (Using Django Allauth)
  - Login and Registration
  - Social Auth
  - Email Activation, Revocvery
  - Password Change, Reset

+ Profile System
  - Custom User Model
  - User Management and Profile
  - Edit User Profile

+ Bootstrap 4 Template System
  - Landing Page
  - Authentication
  - Dashboard
  - Global System Setting (Site name, site title, site email, site address, etc)

+ Error Handler
  - 404 Page not found
  - 500 Server error

+ Email System
  - Email SMTP

+ Database System
  - MariaDb and MySQL
  - SQLite

+ Customizable
  - Built for easy modification and custom editing

<h1>How to Use</h1>

+ Install Python3 and Virtual Environment
  - Install Python3 from <a href="https://www.python.org">Python Software Foundation</a>
  - Create Virtual Environment
    - $ mkdir django-starter && cd django-starter
    - $ python3 -m venv myenv && source myenv/bin/activate

+ Pull source from github
  - $ git clone https://github.com/mymi14s/Django-Project-Starter-Template.git
  - $ cd Django-Project-Starter-Template/src
  - $ pip install -r requirements.txt

+ Create SECRET_KEY, MIGRATIONS and SUPERUSER
  - Generate SECRET_KEY at <a href="https://www.miniwebtool.com/django-secret-key-generator/">miniwebtool</a>
  - Edit core/settings.py line 36
    - Change SECRET_KEY = '<font color="red">9ea*4cwjzn@e9-qhsmkj^%94$8e$=0rgb@%6ort#9(sacs15ui</font>' to new KEY

  - Make Migrations
    - $ python manage.py makemigrations user setting
    - $ python manage.py migrate

  - Create SUPERUSER
    - $ python manage.py createsuperuser
    - $ python manage.py runserver
    - Open http://127.0.0.1:8000/admin/setting/setting/add/ and login
    - Enter Site Information and click save
    - Click on view site from the top menu. ENJOY

+ OPTIONAL CONFIGURATION
  - EMAIL Settings
    - Open core/settings.py and edit with your detail on line 198 to 202

      - EMAIL_USE_TLS = True
      - EMAIL_HOST = 'Your SMTP'
      - EMAIL_HOST_USER = 'YOUR EMAIL'
      - EMAIL_HOST_PASSWORD = 'YOUR PASSWORD'
      - EMAIL_PORT = 587

  - Social Accounts
    - Setup social buttons from core/settings.py from line 62  

  - MYSQL Configuration requires Mysqlclient
    - Visit <a href="https://pypi.org/project/mysqlclient/">Mysql Client</a>
    - Use the instruction provided.
    - Edit core/settings with your mysql database info from line 128.

+ CREDITS
  - Anthony N. Dorothy
  - Pius A. Chukwuelue
  - <a href="https://github.com/pratikborsadiya/vali-admin">Pratik Borsadiya<a/>
  - <a href="https://colorlib.com/demo?theme=creative-agency">ColorLib</a>
