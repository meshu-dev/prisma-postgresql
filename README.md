# Prisma / Postgresql - Hello world example

This is a hello world example of using Prisma to create Postgresql database tables, read and write data.

The code sample for this project is taken from the tutorial available at the [Prisma site](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases-typescript-postgresql).

## Commands

Install packages

    npm run install

Copy .env and fill in 

    npm run install

Create and run migration file from schema

    npx prisma migrate dev --name init

Run index file

    npx ts-node index.ts

