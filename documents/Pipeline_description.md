# Pipeline Process

## CircleCI is used to build this pipeline

<br>

### The configuration of the pipeline contains:

<br>

#### 1- CircleCI install node and aws cli and eb-cli

#### 2- CircleCI checks if there are any changes made to the repo uisng the checkout process

#### 3- CircleCI installs the frontend dependencies and the backend dependencies

#### 4- CircleCI builds the frontend and the backend to make ready for production

#### 5- CircleCI deploys the frontend to S3 bucket and the backend to Elastic Beanstalk

<br>