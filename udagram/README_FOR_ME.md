# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

## Build and Deploy frontend application
https://dzone.com/articles/deploying-an-angular-app-to-aws-s3

1. create a bucket: udacity-webhost-project
2. create scripts to frontend build and deploy
3. setup circle ci for this git reposiory

## Build and Deploy backend
1. create an eb environment:
2. install eb on local computer: https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install-advanced.html
3. init elastic neanstalk: eb init in api repo and configure yaml file
4. create scripts to api build and deploy
5. create postgres database
6. set enviroment variables on elastic beanstalk, see config.ts file
