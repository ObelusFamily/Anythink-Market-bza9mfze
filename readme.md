# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. In the Github codespace, run docker-compose up in the terminal to link the frontend and backend.
2. Visit https://mhwillard-super-duper-garbanzo-wgjp57jpvjg35xpq-3000.preview.app.github.dev/api/ping in a browser window. You should get a "pong" message back if the DB is successfully connected.
3. Visit https://mhwillard-super-duper-garbanzo-wgjp57jpvjg35xpq-3001.preview.app.github.dev/register and test signing up for an account..