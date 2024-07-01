# Project-1
In this project, we will deploy a static website to Amazon S3. We will automate the deployment using the Github Actions.

## Step 1 - Create Amazon S3 Bucket
- Go to the official Amazon documentation on configuring a static website on Amazon S3 https://docs.aws.amazon.com/AmazonS3/latest/userguide/HostingWebsiteOnS3Setup.html. 
- Only complete step 1 — step 4 of the guide and skip step 5 onward.

## Step 2 - Create IAM User
- Create a IAM User with `AmazonS3FullAccess` policy attached to it.
- Copy the Secret and Access ID and keep it saved with you.

## Step 3 - Create Github Repository
- Create a Github Repository
- Go to Settings -> Secrets and Variables -> Actions
- Add the envs there.

## Step 4 - Push the code to Repository
- Pushing the code to repository, will automatically deploy it to S3.