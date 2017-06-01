## Overview

Examples to be used with the [Building and Deploying Microservices with AWS](https://revolutionconf.com/talk/building-and-deploying-microservices-with-aws) workshop at [RevolutionConf 2017](https://revolutionconf.com).

## Install

1. Node.js v6.5.0 or later
2. Serverless CLI v1.14.0 or later --- run `npm install -g serverless` to install.
3. Configure AWS Credentials (instructions below)
  - [Create an IAM user with admin access](http://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html).
  The IAM user you associate with the AWS CLI should have admin permissions, including the ability to create IAM roles.

  - [Configure the AWS CLI to use the admin user](http://docs.aws.amazon.com/cli/latest/reference/configure/)

  - (Optional) [Install the AWS CLI](http://docs.aws.amazon.com/cli/latest/userguide/installing.html) or update the version you to the latest.
4. Run `yarn install`
5. Run `yarn run build:examples` to download node dependencies for all examples OR run `yarn install` inside of each directory.


