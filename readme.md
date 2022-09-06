# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To setup local environment, let do it simpler by breaking down into steps as given below:
-Install docker by [https://docs.docker.com/get-docker/]
-Verify if installed successfully by entering docker-compose -v on terminal
-run docker-compose up from your root folder, it will load frontend and backend part
-have patience, it will take some time
-then go to [http://localhost:3000/api/ping] to test, if alright
-Now go to [http://localhost:3001/register] to load frontend and create your account by providing username etc.

