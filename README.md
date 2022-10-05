# Angular Docker Example

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.3.

# Docker development environment

Here you can find how to use docker to develop

## Docker Compose

Run `docker compose up` for a containerized dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

`CTRL+C` to exit

## Docker Compose Useful Commands

### Run container with build
```
docker compose up --build
```

### Run container in detach mode
```
docker compose up -d
```

### Stop container
```
docker compose stop
```

### Open shell in container (`web` service)
```
docker compose exec web /bin/sh
```


# Local Development

Here you can find instruction to develop without docker

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
