# Hosting a Full-Stack Application

### Description
---
This is the final project from Udacity's FullStack JavaScript Nanodegree. 

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

#### Install
- clone this repo
- navigate in your terminal to the root directory
- run:
        - npm run frontend:intall to install frontend dependencies
        - npm run api:install to install backend dependencies

#### Build
- run:
        npm run frontend:build to build the frontend
        npm run api:build to build the backend

#### Tests
- cd udagram/udagram-frontend
- npm run test
- npm run e2e

There are no tests on the back-end

### Automated Deploy

- Push new commits to the repositori. The pipeline start with the deployment process.

### Link to Application

[App](http://project-hotwing-bucket.s3-website-us-east-1.amazonaws.com)

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
