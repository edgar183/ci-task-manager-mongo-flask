# Task manager application
 
 1. Get data in place first before building application 
    - new DB with as meny collections we need.
 2. Set up flask
    - sudo pip install flask
 3. Create Heroku appliction on heroku website
    - in c9 heroku login
    - check for apps heroku apps
    - local git init and add all files for initila commit 
    - create new repo as instructed in heroku website
    - add requirements file sudo pip3 freeze --local > requirements.txt
    - add Procfile echo web: python app.py (app file) > Procfile
    - git add, commit and push to heroku
    - heroku ps:scale web=1 -start web process
    - set IP and PORT in heroku webist in settings
 4. Install and set up flask python mongo 
    - sudo pip3 flask-pymongo
    - sudo pip3 install dnspython
 5. Set up mongoDB conections in .basrc and in app.py file
    - In mongoDB -> overview -> connect -> connect your application -> copy SRV address
    - export MONGO_URI="link"  .bashrc on root
 6. Use Materialize framework for front end dev http://archives.materializecss.com/0.100.2/
 7. 
 


  