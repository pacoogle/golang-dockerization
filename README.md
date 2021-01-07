# Go in Docker container
This project contains a simple Go server that is running in a Docker container.
Whenever changes are made to the Go code the code is automatically recompiled and run.

## Usage
To spin up the Docker container run
```
make docker-start
```
Then visit `localhost:8080` in your browser to view the API.