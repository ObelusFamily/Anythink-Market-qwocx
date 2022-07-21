# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Start by installing [Docker](https://docs.docker.com/get-docker/). This part of the setup might take a few minutes, but it should be smooth sailing after that.
2. You can verify Docker is ready by running the following commands in your terminal: ```docker -v``` and ```docker-compose -v```.
3. Then, run ```docker-compose up``` from the project root directory to load Anythink's backend and frontend. If Docker is working correctly, the backend should be running and able to connect to your local database.
4. Test that the process went smoothly by pointing your browser to http://localhost:3000/api/ping .
5. Now, it’s time to check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register .
6. Create a new user (choose a cool nickname and everything) and you’ll be able to move to the next task.
7. Now that you have everything set up, just make sure that you run all scripts on one of the containers you created using the ```docker-compose up``` command.  Also, you can use ```docker exec``` to run commands on a running container.


