# Polymer Forex App - Using Starter Kit

[![Build Status](https://travis-ci.org/PolymerElements/polymer-starter-kit.svg?branch=master)](https://travis-ci.org/PolymerElements/polymer-starter-kit)

This is a basic Polymer App for Checking Forex Conversions using fixer.io API

### Quickstart

Fork the repository & clone it to your local server
Fork the node-forex repository from my account and clone it.
Run Polymer Serve --open on your Polymer App folder
Run Node App.js on your node-forex folder
Make sure MongoDb is running

### Setup

##### Prerequisites

First, install [Polymer CLI](https://github.com/Polymer/polymer-cli) using
[npm](https://www.npmjs.com) (we assume you have pre-installed [node.js](https://nodejs.org)).

    npm install -g polymer-cli

Second, install [Bower](https://bower.io/) using [npm](https://www.npmjs.com)

    npm install -g bower

##### Initialize project from template

    mkdir polymer-forex
    cd polymer-forex
    git clone https://github.com/thecheeknee/polymer-forex.git . 
    cd ..
    mkdir node-forex
    git clone https://github.com/thecheeknee/node-forex.git .

### Start the front end server

This command serves the app at `http://127.0.0.1:8081` and provides basic URL
routing for the app:

    cd polymer-forex
    polymer serve --open
    
### Start the back end server

Make sure MongoDb is running. 
This command serves the app at `http://127.0.0.1:8080` and provides basic URL
routing for the app:

    cd node-forex
    node app.js
