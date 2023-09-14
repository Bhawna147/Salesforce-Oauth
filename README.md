# Salesforce Oauth - Django 

Implemented a Salesforce Oauth for a Django app.

Salesforce is a CRM software used by large enterprise companies, it offers API access
and Oauth configuration, that can be publically used by anyone.

Oauth is simply Open Authorization which means that anyone can sign up for an
application by simply using credentials of an already existing application. 

For example -
You all have used Google Oauth, where instead of creating a new account you just use
Sign in With Google to log into an application.


## Install

`pip install django-salesforce-oauth`

## .env

Place a `.env` file inside the `project` folder that contains the following keys
from the OAuth app you configured above:

```
SFDC_CONSUMER_KEY=some_key
SFDC_CONSUMER_SECRET=secret_stuff
```

## django

run migrations and start the server!

---
