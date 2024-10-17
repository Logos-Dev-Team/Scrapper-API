<!-- @format -->

# Scraper Dashboard API

## Requirement System

1. This API build using Express JS (Node JS).
2. For the database, using MongoDB.
3. Manage environtment variable acccording to .env.example file.
4. For email notification made using Gmail service by nodemailer.

## Deployment Step

### `npm install`

Install system depedencies

### `npm start`

Runs the app

#### Notes

Setup First Account -------------------
For first setup, you can crete an account using

### `/user/register` [POST]

with body payload :
{
"username" : "",
"password : "",
"email" : ""
}

Setup Email Notification Service

- You can disable this feature if you dont need this

Go to .env.example file and fill below variable

NODEMAILER_USER='' --> Sender Email
NODEMAILER_PASS='' --> You can find this in Gmail setting or follow this tutorial to gain this password, (https://medium.com/@y.mehnati_49486/how-to-send-an-email-from-your-gmail-account-with-nodemailer-837bf09a7628)
