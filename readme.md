# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Instructions for setting up your environment

- Install ([Docker](https://docs.docker.com/get-docker/)) on your local machince.

- Verify that Docker is ready. Run `docker -v` and `docker-compose -v` in your terminal.

- Run `docker-compose up` from the project root directory to load Anythink's backend and frontend.

- Test your backend is running by pointing your browser to ([http://localhost:3000/api/ping](http://localhost:3000/api/ping)).

- If everything is working properly, you will be able to create a new user at ([http://localhost:3001/register](http://localhost:3001/register)).
