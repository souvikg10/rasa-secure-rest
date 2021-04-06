# Securing your Rasa REST channel

## This is for advanced RASA users only!!

Follow the medium blog here:


>> Note: This repository does not contain all the neccessary installation files for Rasa X/Rasa, you must configure that yourself. This repo only contains the custom configuration needed to secure your Rasa REST endpoint.

## Nginx Configuration
You will find the overridden NGINX configuration at `auth/rasax.nginx` 

## Custom Connector
You will find the custom connector in the `connectors/secure_rest.py`

## Docker-compose and credentials.yml
I have only provided the customised configuration, for the full rasa setup, follow rasa docs

https://rasa.com/docs/