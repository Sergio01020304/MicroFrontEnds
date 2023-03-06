# MicrofrontProyect

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.0.

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


## Commands to configurate modules

ng new microfront-proyect --create-application=false   (Este es el contenedor de todos los proyectos)

ng g application mf-shell --style=scss --routing=true (Este es el contenedor de rutas y mapeo de proyectos)

ng g application mf-shopping --style=scss  (Modulo - Proyecto)

ng generate library commons-lib (Creacion de librerias)

ng add @angular-architects/module-federation --project mf-shell --port 4200 --type host --force (Configuración de modulo host)

ng add @angular-architects/module-federation --project mf-shopping --port 4201 --type remote (Configuración de Modulos remoto)




