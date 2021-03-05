web: gunicorn bot.py 
heroku buildpacks:clear
heroku buildpacks:add --index heroku/python
heroku ps:scale web=1
worker: python bot.py


