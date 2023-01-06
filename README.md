# MyBlog

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

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

## Guide to generate project

# Create module core

`ng generate module core`

# Component header

`ng generate component header --path=src/app/core --module=core --export`

# module shared (rehusable)

`ng generate module shared`

# Componet footer

`ng generate component footer --path=src/app/shared --module=shared --export`

# Creating the contact page

`ng generate module contact`

-- flat won't create a separate folder

`ng generate component contact --path=src/app/contact --module=contact --export --flat`
