# Demo app of flask server connected to postgres

I've been following [this](https://blog.teclado.com/first-rest-api-flask-postgresql-python/) tutorial to set up the server, but I will make changes to reflect more the behavior I want.

To run this, clone it in your machine, and create a virtual env with venv, you can do that running

```
python3 -m venv .venv
```

Then you'll need to create two more files:

- A .env that holds the URL to your database:

```
DATABASE_URL = 'postgre url here'
```

- A .flaskenv that holds env variables for flask:

```
FLASK_APP=app
FLASK_DEBUG=True
```

Afterwards you can activate the venv envoirment running:

```
source .venv/bin/activate
```

And then install de dependencies, by running: 

```
pip install -r ./requirements.txt
```

After this, running <code>flask run</code> on your terminal should start the server.