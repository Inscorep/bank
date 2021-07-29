# Bank

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.2.

## Data Endpoint

https://fun-app-sa-inscorep.azurewebsites.net/api/banks?code=vLRmH0onQsFJwQ35Kccvkr692f4IdaZgSFKBa8O2FwquyOS8N7P2YQ%3D%3D

We decided to only have one data endpoint containing everything for the different sections to simplify things.
You may hit the endpoint wherever needed to extract the relevant data.

## Data Structure

- contact
  - contact details of the bank

- userSettings
  - profile
    - contains the logged in user details

- securitySettings
  - user limits 

- account
  - the user has multiple accounts [Debit Card\Credit Card...] 
  - each account has multiple transactions

## Task

- Create landing page
- fake login page
- user preferences section
- list view of accounts
- detail view of account with a list of transactions

All can be done with or without a css framework.

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
