# Node-postgres-querybuilder

This is a querybuilder intended to generate SQL queries for postgreSQL while relying on the node-postgres npm package to execute the queries.

## Installation

    git clone https://github.com/maqui7295/node-postgres-querybuilder

    cd node-postgres-querybuilder

    yarn install

Next, install postgresql on your local machine and on the terminal, create a database using

    set PGUSER=postgres

    createdb dbname

Or you can use [pgAdmin](https://www.pgadmin.org/) to manage your postgreSQL backend. You can find more information [here](https://www.postgresql.org/docs/11/index.html)

## Usage

To run the application, cd into the root directory and run

    yarn start

This (yarn start) creates the tables and populate it with some dummy data because it runs

    yarn run initdb

Tests, both unit and integration written with [Jasmine](https://jasmine.github.io/) and [supertest](https://www.npmjs.com/package/supertest) can be run with

    yarn test.
