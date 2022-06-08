# ACME coding challenge

## :wave: Welcome!

Here you will find all the details about the **ACME coding challenge** for the candidates who want to join the Winamp Dev Team!

## :blue_book: Summary

The ACME corp. need a web application to manage the stock of their products.

In order to allow the front-end team to develop a wonderful web application, we will need a strong, tested, maintainable and performant back-end API.

## :mag_right: Functional Information

The ACME products have a name, a description, a danger level, a list of pictures, a price in one currency and one universal ID.

The ACME products are stored in Warehouses.

The Warehouses have a maximum capacity of storage, a location and a friendly identifier built as follow: `{country}-{ZIP}-{incremental number of 6 digits}` (e.g: **BE-1070-000001**).

## :hammer_and_wrench: Technical Requirements

- [ ] The code should be a **Fork** of the current Github repository
- [ ] The API should be developed in **.NET 6**
- [ ] The API should expose a **Swagger UI**
- [ ] The API should propose a **paginated** result for each GET
- [ ] The API should be developed in **Domain Driven Design**
- [ ] The API should be **covered by tests** included in the project
- [ ] The API should include logs using **Serilog**
- [ ] The Database should be **PostgreSQL**
- [ ] The Database should be queried using **Entity Framework Core**
- [ ] The whole project should run using a `docker-compose.yml` file (including the database)
- [ ] **EXTRA -** The API should implement a **caching** system to increase the read performances
- [ ] **EXTRA -** The API should be protected by authentication with a **JWT Bearer token**
- [ ] **EXTRA -** The project should embed a basic CI (Build & Test) using the **Github Actions**

## Something is not clear? Any missing information?

It's alright, don't be blocked: you can take assumption to move forward. Let us know why you chose to take this direction. :wink:
