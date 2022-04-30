# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Initial Setup

- Install Docker
    - On windows you can use the WSL 2 backend, see more details [here](https://docs.docker.com/desktop/windows/wsl/0)
- Start the environment by running `docker-compose up` from the project root directory
- If everything is OK, you'll be able to access the UI at http://localhost:3001/

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
