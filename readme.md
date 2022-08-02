# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Steps required

1) Open the local repository and clone it in your local machine
2) Add any missing file in the repository in the following steps
    1) Create a new branch
    2) Add the file to the root repository(the main folder having all sub-folders)
    3) Commit the change
    4) Push it
3) Create a pull request and thus merge your branch with main 
4) Install Docker from here: https://docs.docker.com/get-docker/
5) Verify the docker is ready for running by running commands `docker -v` and `docker-compose -v` in terminal
6) Test this by pointing your browser to http://localhost:3000/api/ping
7) To check the frontend you’ll be able to create a new user on http://localhost:3001/register
