# Using CodePipeline to move a CloudFormation template on GitHub to S3 Bucket.
This Project was practice using a AWS CloudFormation to automate a static website on AWS S3 through AWS CodePipeline. Every part of this project was example code.
#
**Steps**
1. Create a Repository on GitHub and add a simple CloudFormation template to create a s3 Bucket.
2. Create a service role for CodePipeline using Iam. (Customize an ec2 role’s trust entity to fit for CodePipeline)
3. Create a service role for CodeFormation, add the s3 full access policy.
4. Create a Pipeline in CodePipeline.
5. 
