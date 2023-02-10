# Python Serverless

Python Serverless POC to do basic things with AWS Lambda and API gateway.


## Instructions

The project is versioned according to each successful addition of functionality. (ie. in version v1.0.0 creates a basic hello world post endpoint. checkout to the tag to run the listed features)


# v1.0.0 Basic Python POST method 

This is the basic POC to return a message while posting to the create API. 

1. Configure accounts (You will need a serverless account linked with your AWS account. You can simply do this by creating a GitHub account and then logging into your serverless account via Github. Then also log into your AWS account and add a provider in serverless, it will create a Cloudformation stack that deploys the roles for your serverless app.) 

2. Create an app in serverless, name it `demopy`. (This has to be the same as declared in the serverless.yml file)

3. After creating the app in serverless open a terminal in the root of this directory and enter `sls deploy`

4. Then Check the progress and debug (see the serverless console as well as AWS Cloudformation console.)

5. Hit a POST request to the provided URL


# v2.0.0 Athunticate API with Keys

Addition to the basic POC utilizing API key.

1. After checking out to tag v2.0.0 just run `sls deploy` again

2. Then Hit the POST request to the provided URL with a Header `x-api-key` with the provided API key