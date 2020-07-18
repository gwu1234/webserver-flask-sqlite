it is a demo project of python flask web server. It has a sqlite database, and html/css ui

To test on local host:

1) create sqlite data file:

python3 (to start python command line)

from app import db

db.create_all()

exit()

2) start the web server 

python3 app.py



