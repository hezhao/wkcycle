wkcycle
=======

Bike Commute Challenge with [Moves](https://www.moves-app.com/) app, it logs your trips, and calcualtes your average daily, weekly, and monthly bike commute speed betwen your home and work, and compare your trips with other cyclists globally.

### Getting Started
1. Apply for a [Moves API](https://dev.moves-app.com/) key
2. Create a redis database (e.g. You can create one for free at [redistogo](http://redistogo.com/))
3. Put in `MOVES_CLIENT_ID`, `MOVES_CLIENT_SECRET`, `REDIS_URL`, `FLASK_APP_SECRET` in `env`
4. `$ source env`, or if you use [Autoenv](https://github.com/kennethreitz/autoenv) simply `$ cp env .env`

### Debug on Local Machine
	$ python run.py
    $ open http://0.0.0.0:5000

### Usage

1. Go to http://wkcycle.herokuapp.com
2. Register with a valid email addresss
3. Connect with Moves app
4. Label your home and work, if necessary also label bike rides between them (usually Moves app is smart enought to automatically label this)
