# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To set up a local environment for the first time, install Docker on your system. 

Once this is done, ensure it's properly set up by running "docker -v" and "docker-compose -v" in your terminal.

Next, navigate to the Anythink root directory and run "docker-compose up". NOTE: Make sure Docker is currently running.

After this is done, test your local connection here: http://localhost:3000/api/ping 

If this works, then follow this link to complete your first-time account setup: http://localhost:3001/register 