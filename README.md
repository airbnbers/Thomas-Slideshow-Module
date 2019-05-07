# Bearbnb Slideshow Module
For Bearbnb sample product page.  This app was kept lightweight by using only React, Bootstrap, Express, PostgreSQL, Knex.js, and a healthy dose of CSS. This page utilizes responsive design layouts for large to mobile screen sizes.

This service is currently deployed on AWS Elastic Beanstalk at http://bearbnbphotos.us-east-2.elasticbeanstalk.com/rooms/1/.  Additional listings can be found at endpoints /rooms/1 to /rooms/100. This page was original displayed on a proxy page along with a booking and reviews service.

## Related Projects

  - https://github.com/airbnbers/ - For proxy server, booking, and reviews services.

## Table of Contents

1. [Usage](#Usage)
2. [Requirements](#requirements)
3. [Development](#development)

## Usage

1. Ensure postgreSQL is install and running.
2. Install with 'npm install'.
3. Create a config.js file with your postgreSQL password.
4. Generate data with 'npm run seed'.
5. Build bundle.js with 'npm run build-webpack'.
6. Run service with 'npm start' and visit `http://localhost:3001' to view service.

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

## Development
Test:
> npm test

Create config.js with your database password.

### Installing Dependencies

From within the root directory:

```sh
npm install -g webpack
npm install
```
