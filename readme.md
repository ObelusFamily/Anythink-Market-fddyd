# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install Docker
- Run `docker -v` and `docker-compose up` to validate that docker has been installed correctly
- Run `docker-compose up` from the project root directory
- Validate that the backend is running by pointing your browser to `http://localhost:3000/api/ping`
- Validate that the frontend is running by pointing your browser to `http://localhost:3001/register`
- Using the previous link, please create a new user
- You are all set up!