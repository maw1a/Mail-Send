# Mail Send

## About

This repository is the backend for sending mails using MailGun API.

## Setup

Rename .env.exmaple file to .env and add MAILGUN_API_KEY and the MAILGUN_DOMAIN. These can be found in your mailgun account.
Add Reciever's Address in place of RECIEVER_EMAIL_ADDRESS. This will be your email address in case of a contact form.

## Hosting

A Procfile has been created for heroku hosting of this backend. POST **/send** route will send the email to the reciever's email.
The POST body must have:

- Name of the Sender
- Email of the Sender
- Subject of the Email
- Body of the Email
