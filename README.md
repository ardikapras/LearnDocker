#LearnDocker

This repository is for learning purpose, to build complex Docker for multiple instance/server.

## Tech/framework used

Client - React App (Fibonacci app)
Server - NodeJS / ExpressJS
Worker - Redis
HTTP Server - Nginx

## Installation

Run 'docker-compose up --build' on the root folder, to build the images and start up the server. Subsequently, can run 'docker-compose up' if there is no changes on docker build file or compose.
Run 'docker-compose down', to stop the Docker compose.

## How to access

Run in browser, http://localhost:3050/ , to show client frontend.
Run, http://localhost:3050/api/values/all ,to access server directly.