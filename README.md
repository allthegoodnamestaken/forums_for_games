# forums_for_games
 
## Installing

`pip install -r requirements.txt`

You may need to 
`python -m pip install pip
 python -m pip install pillow`
 
 if pillow doesn't install correctly initially.
 
 ## Running
 
 `python manage.py runserver` 
 
 will start the server on 127.0.0.1. Note that you'll have to go to /forums in order to actually see anything. I'll fix this later.
 
 `python manage.py createsuperuser`
 
 will start a process to register an admin user. There's no regular registration page right now, so you'll have to use this until I make one or figure out how to turn on a machina page. 
