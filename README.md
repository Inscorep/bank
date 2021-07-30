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
