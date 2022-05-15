# Documentation of the projects
## 1. Flow of execution
1.1 Creat a react app using "npx create-react-app demo-app", then move to the demo-app directory and check the app using "npm start" command.
1.2 Use "npm run build" command to build a app. Then push the react app to github repo.
1.3 Open a aws console, create two S3 bucket one for main url "www.happynehra.com" and other for redirecting react app to main url. Then upload a react app to S3 bucket.
1.4 Link for S3 bucket [http://www.happynehra.com.s3-website.ap-south-1.amazonaws.com](http://www.happynehra.com.s3-website.ap-south-1.amazonaws.com).
1.5 Add a Cloudfront Distribution for the S3 bucket. Link for Cloudfront [d19n4jwid3oer4.cloudfront.net](d19n4jwid3oer4.cloudfront.net).
1.6 Open git and make another branch "release". push it to github repo. Create a yml file for codebuild.
1.7 Open aws console and create codepipeline.
1.8 Create SNS notifications (to email) for code pipeline stages.

## 

