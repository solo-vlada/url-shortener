LAP 4 Code Challenge
URL Shortener 

Installation & Usage 
1. Run pipenv install flask
2. Run pipenv shell
3. Run pipenv install python-dotenv
4. Run pipenv install flask-sqlalchemy
5. Run flask run to start the server

Database set up
1. Run python
2. Run from url_shortener import create_app
3. Run from url_shortener.extensions import db
4. Run from url_shortener.models import Link
5. Run db.create_all(app=create_app())
6. exit()

Database access
1. Run sqlite3 url_shortener/db.sqlite3
2. Run select * from link;
3. .exit

CHANGELOG

Configuration
1. Added .env and .flaskenv files with configurations
2. Created url_shortener folder and added settins.py
3. Imported configurations from .env into settings.py
5. Created extensions.py
6. Imported SQLAlchemy and created a db instance 

App:
4. Created models.py
7. In models.py created class Link. Link includes id, original url, short url, number of visit to the link, date of link creation.

8. In models.py added a function to generate a random path for short_link
9. In routes.py added routes for the homepage, creating short link, results page, stats page and 404 page 

10. Created templates directory
11. Added a form in index.html for the homepage, results page, stats page and 404 page 
12. Used bulma to add styling 




