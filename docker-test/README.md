# Docker Test Project

This is a simple Go project that is built and run using Docker.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Go 1.21.6
- Docker

### Building

To build the Docker image for this project, run the following command:

```sh
docker build -t docker-test .

# or (if you have make installed)

make build
```

### Running

To run the Docker image for this project, run the following command:

```sh
docker run docker-test

# or (if you have make installed)

make run
```
