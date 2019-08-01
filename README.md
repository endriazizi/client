# MyApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.1.0.

# Modules

`npm install materialize-css@next --save`

ng g component components/authTabs --dry-run
ng g module modules/auth-routing --flat --dry-run
ng g module modules/auth --flat --dry-run

ng g component components/login --module=modules/auth.module.ts --dry-run
ng g component components/signup --module=modules/auth.module.ts

ng g service services/auth --no-spec --flat

<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <title>MyApp</title>
    <base href="/">

    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="icon" type="image/x-icon" href="favicon.ico">

</head>

<body>
    <app-root></app-root>

</body>

</html>

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
