# micro-minding
A repo for a micro service real time application using multiple languages and gRPC for communication. The goal of the application is to provide a real time mind-map that can be used by multiple different people. The application is written in golang, node.js, react and uses gRPC internally for communication.

# Building and Starting 

To run this application you will need docker installed.

## Running a single container
```bash
$ # Build a single containers
$ docker-compose build [container-name]

$ # Run a single container
$ docker-compose up [container-name]
```

## Running all containers
```bash
$ # Build the containers
$ docker compose build

$ # Run all containers with dependencies
$ docker compose up
```
