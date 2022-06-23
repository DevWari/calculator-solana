# Calculator

As you are applying for a senior role in EraMeta, we expect that you have an excellent
understanding of Angular and can design small-scale applications, which are able to
communicate with the backend.

Please view this video of our launchpad MVP:
https://twitter.com/EraMetaDAO/status/1513534454454697998?s=20&t=LG4I9V5i62Q3JRnSp2aI0Q


TASK 1: Arweave Cost Calculator:

Design:


As a user who wants to deploy my candy machine through EraMeta, I would like to know how
much SOL to have in my wallet in order to cover all of the uploading costs. Storing image files
permanently through Arweave is not free and this cost should be calculated for the user before
they decide to upload their Solana NFTs through EraMeta. The uploading costs include
Arweave storage cost calculated in USD per MB.


Task:

Implement a front-end app that calculates the Arweave permanent storage cost. First, the user
is prompted to connect their Solana wallet which should redirect them to a separate page upon
a successful connection. On this next page, users are asked to select or drop as many image
files as they would like. Once the user generated files have been stored in memory, the user
should be able to click a “calculate” button. Upon clicking “calculate”, the program should fetch
relevant data from Arweave in order to calculate the permanent storage cost. Once the cost has
been calculated, the program should present a pop-up modal that displays the total storage cost
as well as whether or not the user has enough funds in his wallet.

*Please make the UI as beautiful as you can, using your own design guidelines. Any animation
or unique design is a bonus.*


Implementation:

Front-end: Angular
Back-end: ExpressJs (if needed)
Storage: Firebase (if needed)
References:

Arweave - https://www.arweave.org/

Arweave calculator - https://arweavefees.com/




This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.2.

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
