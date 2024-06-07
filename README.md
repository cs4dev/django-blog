# Getting Started

## Prerequisite
python >=3.10

## Creating a Python virtual environment
```
python3 -m venv my_env
```
## Activate virtual environment
```
source my_env/bin/activate
```
## Install dependencies
```
cd jonlim && pip3 install -r requirements.txt
```
## Create a new file .env on the project's root directory, jonlim, set up external SMTP configuration to send emails
```
EMAIL_HOST_USER=
EMAIL_HOST_PASSWORD=
DEFAULT_FROM_EMAIL=
```
## Start Development Server
```
cd jonlim && python3 manage.py runserver
```
## Open in your browser
```
http://127.0.0.1:8000/blog
```
