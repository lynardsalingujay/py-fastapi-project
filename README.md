# py-fastapi-project

## clone the repo

git clone git@github.com-personal:lynardsalingujay/py-fastapi-project.git

## Create a virtual environment

python -m venv venv

## Activate the virtual environment

source venv/bin/activate

## Install FastAPI and Uvicorn

`pip install fastapi uvicorn`

## to run the fastapi application

uvicorn main:app --reload
> The --reload flag enables automatic reloading of the server upon code changes, which is useful during development.
