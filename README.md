# AngularCitations

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.2.0 and upgraded to the latest angular version (13.1 for instance at 17/12/2021)

With Angular 10.2.0, tailwindcss requires thoses steps to run finely :
 * Usage of TailwindCSS with the help of this : https://medium.com/@jacobneterer/angular-and-tailwindcss-2388fb6e0bab
 * To install Tailwind, follow https://camerondwyer.com/2020/07/09/using-tailwind-css-in-an-angular-cli-app/ 
 * Take care woz you will need to install postcss@8, because by default it installs v7 (https://stackoverflow.com/questions/63858991/how-to-setup-tailwind-for-a-new-angular-project)
 * Also follow this https://fullyunderstood.com/get-started-with-angular-tailwind-css/ because it helps to reduce the the size of styles (the tailwind.config.js is the solution)

But with Angular 11.2, it's more simpler and there is no more needs to all these hacks (thanks for them coz it really helped me on those times).

In the last few days, i also added the package @angular/pwa to allow the lighthouse benchmark to improve the notation.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
