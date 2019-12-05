## Face-Recognition-App-Backend
The back-end of a JavaScript website that is used to highlight faces of random images.   

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Features](#Features)
* [Website](#Website)
* [Setup](#setup)

## General info
A JavaScript website that is used to highlight faces of random images. The purpose of this project was to advance my skills with React's framework to make a functional website. This website uses a Machine Learning API Key called Clarifai to provide a location of a person's face when given an image. The front-end consumes a Rest Service built of Express (Node.js back-end server) and Postgres SQL (Relational Database). The database stores account information such as name, email, password, number of image entries, and timestamp. The website is deployed through Heroku.

## Technologies
* React.js - version 16.12.0
* Express (Node.js) - version 4.16.2
* Postgres SQL - version 7.14.0
* Clarifai - version 2.9.1
* Bcrypt (Node.js) - version 0.0.3
* Body Parser - version 1.19.0
* CORS - version 2.8.5
* Knex - version 0.14.6
* React Particles.js - version 2.7.0
* React Tilt - version 0.1.4
* Tachyons - version 4.11.1
* JSON

## Features
* Passwords are encrypted and stored on the Postgres database using Bcrypt.
* Clarifai's Machine Learning API is used to detect images that contain a person's or persons' face(s).

## Website
[Face Recognition App](https://face-recognition-program.herokuapp.com/)

## Setup
After you clone this repo to your desktop, go to its root directory and run `npm install` to install its dependencies.
Once the dependencies are installed, you can run  `npm start` to start the application. You will then be able to access it at localhost:3001
