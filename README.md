## Description

Learn NestJS

## Installation

Requirements
- NodeJS
- Docker

```bash
$ npm ci
```

## Running the app

```bash
# Run docker first
$ docker-compose up -d

# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Migration

```bash
# Create new migration
$ npx typeorm migration:create ./src/migrations/CoffeeRefactor

# run migration - make sure to run `npm run build`
$ npx typeorm migration:run
```
## License

Nest is [MIT licensed](LICENSE).
