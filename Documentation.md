# FLow of execution
1. Bootstrap a `create-react-app` project.
2. Created a new repository on github & pushed the code there.
3. Created a free account on AWS.
4. Deployed the app on S3 (config to be done for routes).
5. Added a Cloudfront Distribution for the S3 bucket.
6. Created code pipeline step, triggered on code change of `release` branch.
7. Created code build step, generates the react build artifact.
8. Created code deploy step, took the artifact from previous step & deploys it to s3/cloudfront.
9. Connected domain to cloudfront distribution.
10. Attached SSL certificate to enable https on cloudfront distribution.
11. Created SNS notifications (to email) for code pipeline stages, (started/succeded/failed) on tanmay@octoapp.ai, mithilesh@octoapp.ai & happynehra777@gmail.com

### Routes for app 
[www.happynehra.com](www.happynehra.com)
[happynehra.com](happynehra.com)

### S3 bucket link
[http://www.happynehra.com.s3-website.ap-south-1.amazonaws.com](http://www.happynehra.com.s3-website.ap-south-1.amazonaws.com)

### Cloudfront Dristribution link
[https://d1tgk0v6gzwr9y.cloudfront.net](https://d1tgk0v6gzwr9y.cloudfront.net)
