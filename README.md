# AMedium

AMedium is a clone of Medium.

## Requirements

- [Docker](https://docs.docker.com/install/) >= *v*19.03.2
- [Docker Compose](https://docs.docker.com/compose/install/) >= *v*1.23.2

## Services

### AMedium App [![CircleCI](https://circleci.com/gh/AlexisNava/AMedium-App/tree/master.svg?style=svg)](https://circleci.com/gh/AlexisNava/AMedium-App/tree/master)

- Description: SPA for the AMedium project.
- Repository: https://github.com/AlexisNava/AMedium-App

### AMedium Auth [![CircleCI](https://circleci.com/gh/AlexisNava/AMedium-Auth/tree/master.svg?style=svg)](https://circleci.com/gh/AlexisNava/AMedium-Auth/tree/master)

- Description: RESTful Service of Authentication for the AMedium.
- Repository: https://github.com/AlexisNava/AMedium-Auth

## Usage

### Run all the services

```sh

docker-compose up

```

### Run all the services in detach mode

```sh

docker-compose -d up

```

### Stop all the services

```sh

docker-compose stop

```

### Remove the data in all the volumes

```sh

docker-compose down --volumes

```

## License

**AMediumServices** is licensed under [Apache License, Version 2.0](https://github.com/AlexisNava/AMediumServices/blob/master/LICENSE).
