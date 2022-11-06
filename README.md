# FastAPI minimal - database

Minimal example of using FastAPI with a database via SQLAlchemy.


> Requires python 3.10 or above
> Using an older version of python and can't upgrade?
> See https://github.com/chrisjsimpson/fastapi-database-example

# Install

```
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
```

# Run
```
. venv/bin/activate
uvicorn sql_app.main:app --reload
```

Visit http://127.0.0.1:8000/docs

See https://fastapi.tiangolo.com/tutorial/sql-databases/

# Looking for a more complete guide?

See [Example FastAPI tutorial with automated deployment](https://github.com/chrisjsimpson/fastapi)
