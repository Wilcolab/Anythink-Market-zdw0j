# Welcome to the Anythink Market repo

To start the app use [Docker](https://docs.docker.com/get-docker/). After installing Docker, you can verify that it is installed by running `docker -v` in your terminal. When you are ready to start the app, run `docker-compose up`. It will start both frontend and backend, including all the relevant dependencies, and the db.

To test that the backend is running, go to [http://localhost:3000/api/ping](http://localhost:3000/api/ping). If everything is working, test the frontend by going to [http://localhost:3001/register](http://localhost:3001/register) and creating a new user.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
