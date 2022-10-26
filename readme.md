# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Loading Anythink's Frontend and Backend

1) Run Docker Desktop first in your laptop
2) In your root project directory, open up a terminal. I use git bash.
3) Run `docker -v` and `docker-compose -v` to check if docker is up and running
4) Run `docker-compose up` in your root directory to load Anythink's frontend and backend
5) If docker is running, your backend should be running and able to connect to the local database. Check this by clicking http://localhost:3000/api/ping
6) Check that frontend is running and connected to backend as well. Redirect your browser to http://localhost:3001/register
7) Create new user and register
8) Done! Repeat these same commands for the next projects to setup the docker compose and load up the frontend and the backend. Run the scripts in the running container by `docker-compose up` command or `docker exec` to run commands in a running container.
