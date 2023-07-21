## Pipeline Description

in the pipeline
1. code is written in vscode
2. using git commands, code is staged, commited and pushed to a github repo
3. once new code hits repo. CircleCI has been integrated with repo to build and deploy

### CicleCI
1. once new commit pushed, circleCi will start the build process and run a build command on backend and frontend code
2. will be placed in a hold status for owner to review and approve
3. once approved, deploy steps will occur...successfully deploying to AWS Elastic Beanstalk and updated s3 bucket for hosting