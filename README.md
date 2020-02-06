**Install the app:**
Install pipenv https://github.com/pypa/pipenv
Install pyenv https://github.com/pyenv/pyenv
```
pyenv install 
pipenv install
```

**Run the app:**
```
pipenv shell
FLASK_RUN_PORT=8011 FLASK_APP=file_upload.py flask run
```

**Ping the app:**
```
curl http://127.0.0.1:5000/
```
