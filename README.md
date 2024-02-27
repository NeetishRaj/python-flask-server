# Python | Flask  | Website hosting (templates)

## Project setup

```
# install pip if not available
sudo apt install python3-pip

# install flask
pip install flask

```

## To start server

```
python3 app.py
```

## Folder structure as per Flask

1. All the publically available static content goes to `static` folder.
2. ALl the templates i.e html files goes to `templates` folder


## set up virtual env to precent global package installs

```
pip3 install virtualenv


# create a virtual environment named 'env'
virtualenv env

# to start working in the new environment console
source env/bin/activate
```