# Smart-Brain App: serverless AWS Lambda function.
Code for the Lambda function used in the React SmartBrainApp for demostration purposes.

https://github.com/gerrcass/smart-brain-frontend/blob/12b598f36c98829ca7e510370e00aefc21643afe/src/components/Rank/Rank.js#L28

For your own lambda function, you'll need AWS Free Tier to get your AWS credentials (IAM user + Programmatic access available).

## For this function to be in the cloud:

1. Install globally the serverless npm package: **npm install -g serverless**

2. Run: **sls create -t aws-nodejs**

3. Run: **sls config credentials --provider aws --key YOUR_ACCESS_KEY --secret YOUR_SECRET_ACCESS_KEY**

4. Run: **sls deploy**

![sls deploy](https://github.com/gerrcass/smart-brain-serverless-aws-lambda/blob/master/sls_deploy.jpg)
