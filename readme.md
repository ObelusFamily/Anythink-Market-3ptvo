# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup (MacOS)

Install Docker via [Homebrew](https://formulae.brew.sh/cask/docker#default):

```bash
brew install --cask docker
```

Verify docker is ready by running either command: `docker -v` or `docker-compose -v`.

## Run the container

Run `docker-compose up` from the project root directory to start the container.

## Frontend nd backend

When everything is running, check that the container's backend can connect to the local db at `http://localhost:3000/api/ping`

To see the frontend and create a new user, navigate to `http://localhost:3001/register`
