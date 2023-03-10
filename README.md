# ๐ Nest.js REST API ๐ด

## Description

This is a simple RESTful API built using [Nestjs](https://nestjs.com/), which is a progressive Node.js framework for building efficient, reliable and scalable server-side applications.

โ ๏ธ This is currently a work-in-progress endeavour, but I plan for it to be a simple API for a blog.

## ๐ Tech Stack

- [Nest](https://nestjs.com/) ๐
- [Prisma ORM](https://www.prisma.io/) โง
- [Postgres DB](https://www.postgresql.org/) ๐
- [Jest](https://jestjs.io/) ๐งช ๐ฅผ ๐ฌ

  - [@nestjs/config](https://www.npmjs.com/package/@nestjs/config)
  - [@nestjs/jwt](https://www.npmjs.com/package/@nestjs/jwt)
  - [@nestjs/passport](https://www.npmjs.com/package/@nestjs/passport)
  - [Argon](https://www.npmjs.com/package/argon2)
  - [class-validator](https://www.npmjs.com/package/class-validator)
  - [passport](https://www.npmjs.com/package/passport)
  - [passport-jwt](https://www.npmjs.com/package/passport-jwt) \*
  - ...

## ๐ฆ Installation

```bash
 pnpm install
```

## ๐ Running the app

```bash
# development
 pnpm run start

# watch mode
 pnpm run start:dev

# production mode
 pnpm run start:prod
```

## ๐ก Connect to the db

```bash
#spawn the docker image & run migrations **automatically**
pnpm db:dev:restart

# visualize data
pnpm exec prisma studio
```

## ๐งช ๐ฅผ Test

```bash
# unit tests
 pnpm run test

# e2e tests
 pnpm run test:e2e

# test coverage
 pnpm run test:cov
```
