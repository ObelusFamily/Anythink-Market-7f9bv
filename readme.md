# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone this repo to your local machine
2. Install Docker - https://docs.docker.com/get-docker/
3. Verify that Docker is ready by running `docker -v` and `docker-compose -v` in your terminal
4. Navigate to the projects root directory and run `docker-compose up`
5. After the Docker is up check that the Backend is working by navigating to http://localhost:3000/api/ping and see that you get a response
6. Check that the Frontend is ready by navigating to http://localhost:3001/register and creating a new user
7. User `docker exec` to run scripts on a running container
