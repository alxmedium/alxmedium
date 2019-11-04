# AMedium

AMedium is a clone of Medium.

## Requirements

- [Docker](https://docs.docker.com/install/) >= *v*19.03.3
- [Docker Compose](https://docs.docker.com/compose/install/) >= *v*1.24.1

## Services

<details>

<summary>See the services list</summary>

### AMedium App [![CircleCI](https://circleci.com/gh/AlexisNava/AMedium-App/tree/master.svg?style=svg)](https://circleci.com/gh/AlexisNava/AMedium-App/tree/master)

- Description: SPA for the AMedium project.
- Repository: [AMedium-App](https://github.com/AlexisNava/AMedium-App)

### AMedium Auth [![CircleCI](https://circleci.com/gh/AlexisNava/AMedium-Auth/tree/master.svg?style=svg)](https://circleci.com/gh/AlexisNava/AMedium-Auth/tree/master)

- Description: RESTful services of the Authentication module for the AMedium project.
- Repository: [AMedium-Auth](https://github.com/AlexisNava/AMedium-Auth)

</details>

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
