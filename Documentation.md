# FLow of execution
1. Bootstrap a `create-react-app` project.
2. created a new repository on github & pushed the code there.
3. Created a free account on AWS.
4. Deploy the app on S3 (config to be done for routes).
5. Add a Cloudfront Distribution for the S3 bucket.
6. Created code pipeline step, triggered on code change of `release` branch.
7. Created code build step, generates the react build artifact.
8. Create code deploy step, takes the artifact from previous step & deploys it to s3/cloudfront.
9. Connected domain to cloudfront distribution.
10. Attached SSL certificate to enable https on cloudfront distribution.
11. Created SNS notifications (to email) for code pipeline stages, (started/succeded/failed) on tanmay@octoapp.ai, mithilesh@octoapp.ai & happynehra777@gmail.com
