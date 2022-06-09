# Udagram

The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

### Dependencies

```text
- Node v14 (LTS)

- npm 5.5.3

- AWS CLI v2

- AWS EB CLI

- AWS RDS database running Postgres

- AWS S3 bucket for Frontend

- AWS Elastic Beanstalk for Backend

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <mydb.crkfsuo6dghd.us-east-1.rds.amazonaws.com>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <http://abbas-udagram-bucket.s3-website-us-east-1.amazonaws.com>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd udagram/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd udagram/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## Deployment

- [http://udagram-yasser.s3-website.us-east-2.amazonaws.com](http://udagram-yasser.s3-website.us-east-2.amazonaws.com) - S3 Bucket - udagram-frontend
- [![Build Status](https://circleci.com/gh/yasser1412/udagram.svg?style=shield)](https://circleci.com/gh/yasser1412/udagram)

## Documents

### Click [here](https://github.com/yasser1412/udagram/tree/main/Documentation) to open the Documents
