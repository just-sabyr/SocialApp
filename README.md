# Bookmarks Web App 

## Demo Video
TODO

## Create an OAuth2 API in Google Cloud Project
-- Refer to the book on how exactly this is done

## Create a python venv
```bash
    python3 -m venv venv
```

## Clone this repo
```bash 
    git clone https://github.com/just-sabyr/SocialApp.git 
```

## Change directory to src
```bash
    cd SocialApp
```

## Activate the venv
```bash
    source ../venv/bin/activate
```

## Install the required Python libraries
```bash
    pip install requirements.py
```

## Create .env file (sample is `sample_env` file in this repo)
```bash
    touch .env
```

## Make migrations & migrate
```bash
    python manage.py makemigrations
    python manage.py migrate
```

## Run this project locally
```bash
    python manage.py runserver
```

