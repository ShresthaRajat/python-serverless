# Python Serverless

Python Serverless POC to do basic things with AWS Lambda and API gateway.


## Instructions

The project is versioned according to each sucessfull addition of functionality. (ie. in version v1.0.0 creates a basic hello world post endpoint. checkout to the tag to run the listed featues)


# v1.0.0 Basic Python POST method 

This is the basic POC to return a message while posting to the create api. 

1. Configure accounts (You will need a serverless account linked with your aws account. You can simply do this by creating a Github account and then logging into your serverless account via Github. Then also log into your aws account and add a provider in serverless, it will create a cloudformation stack which deploys the roles for your serverless app.) 

2. Create a app in serverless, name it demopy. (This has to be the same as declared in the serverless.yml file)

3. After creating the app in serverless open a terminal in the root of this directory and enter `sls deploy`

4. Then Check the progress and debug (see the serverless console as well as aws cloudformation console.)