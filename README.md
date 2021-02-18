# Overview

Learing how to use flask-login for user authentication

Following tutorial: https://www.digitalocean.com/community/tutorials/how-to-add-authentication-to-your-app-with-flask-login


# Installation

A database must be created before the app can be run locally. Navigate to the project root-directory, and execute the following commands from a python shell:

    from project import db, create_app
    db.create_all(app=create_app())


# Usage

This app can be run using Flask's built-in server.

First, populate two environment variables used by Flask:

    export FLASK_APP=<project-directory>
    export FLASK_DEBUG=1

Next, run the app from the root project folder with the following command:

    flask run
