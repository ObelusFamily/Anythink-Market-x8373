# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To setup your local environment perform the following steps:
1. Clone this repository `git clone git@github.com:ObelusFamily/Anythink-Market-x8373.git`
2. Install [Docker](https://www.docker.com/products/docker-desktop/)
3. Run `docker-compose up`
4. Test it's working by accessing the backend at `http://localhost:3000/api/ping` and the frontend at `http://localhost:3001`