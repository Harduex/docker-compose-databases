# Docker Compose Database Collection

This collection of Docker Compose files help you to run any database server, fast and easy.

## Prerequisites

Before you can use these Docker Compose files, you'll need to have Docker and Docker Compose installed on your machine. You can find instructions on how to do that in the [Docker documentation](https://docs.docker.com/).

## Usage

To use this collection, simply navigate to the desired database folder and update the `.env` file with your desired values:

- `DB_PORT`: The port on which the database will be running.
- `DB_DATABASE`: The name of the database.
- `DB_USERNAME`: The username for the database.
- `DB_PASSWORD`: The password for the database.

Once you've updated the `.env` file with your desired values, run the following command to start the container in detached mode:

```
docker compose up -d
```

To stop the container, run the following command:

```
docker-compose down
```

## Contributing

If you would like to contribute to this project, feel free to create a pull request with your changes.
