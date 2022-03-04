# FLASK DEMO

This repo is about basics of flask api and how to deploy a machine learning web application in heroku

- pip install gunicorn in our venv
- create Procfile
- make requirements.txt file with command pip freeze > requierments.txt


## Commmon mistakes  to avoid error in heroku
1 . check spelling
   - your app name sholud be in app.py only becauses its connected with gunicorn
   - spelling for requirements.txt---------not requirement.txt ---missing 's'
   - spelling for Procfile---------'P' sholud be in uppercaps
   - spelling for templates---------lowercase for 't' and and not tempalte ---missing 's'

2 . gunicorn mistakes
   - not installed gunicorn-----check your requirements.txt for gunicorn.
   - Procfile error
