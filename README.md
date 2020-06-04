# aws-lambda-github-action
aws-lambda-github-action

There two lambda functions.
1. Foo Function ( api/foo )
2. Bar Functions ( api/foo )


## Github Action Workflows
There are 2 workflow files
1. foo-api.yml 
2. bar-api.yml 

Github detects the change on `api/foo` and `api/bar` respectively and triggers workflows.
Job consists of steps for node setup, npm build, zip, and deploy to AWS.

