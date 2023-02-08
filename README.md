#### app.controller.ts - Establish the API endpoint, accept requests, and send the returned response.
#### app.module.ts - The @Module() decorator provides metadata that Nest makes use of to organize the application structure. At last I apply middleware to all the route of this controller.
#### app.service.ts - wrote the controller code for the API logic for a certain endpoint.
#### main.ts - This is the application's starting point. Here, after importing a function from redis.ts, define the port and connect to Redis. 
#### redis.ts - The redis npm package is used here. Create a redis instance and connect to its default port, which is 6379. Finally, I export the function and instance needed to connect to Redis.
#### rate.limitter.middleware.ts - This middleware function handles all of the rate limiter's logic. I make my own middleware for nest.


## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
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
