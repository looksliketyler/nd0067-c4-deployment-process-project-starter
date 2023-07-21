  ## Overview
  there are a few components uses in AWS for this project  RDS, Elastic Beanstalk and S3 Bucket. All are public access.

  ## AWS Services
  #### - RDS 
    name: keywork-db
      used for a postgres database to save information. using default region of us-east-1

  #### - Elastic Beanstalk - to house the backend api
    name: 'udagram-api'
      environment as 'udagram-api-dev'
      environment id as 'e-xuviyxhpup'
      running Node.js 14 running on 64bit Amazon Linux 2/5.8.3

  #### - s3 Bucket - to host the entire application for use
    name: keywork
      hosted in us-east-1
      arn as 'arn:aws:s3:::keywork'
      holds the build files of the frontend angular application