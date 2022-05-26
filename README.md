# AWS Terraform Templates

This repo has a collection of AWS terraform templates, that I have worked on from past few years.

## **Pre-requisite:**
- Install terraform on your system
- Install AWS cli on your system
- Should have AWS Account.
  - [Create an AWS Account](https://portal.aws.amazon.com/billing/signup?nc2=h_ct&src=header_signup&redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation#/start)
- Generate Security Credentials using AWS Management Console
  - Go to Services -> IAM -> Users -> "Your-Admin-User" -> Security Credentials -> Create Access Key
- Configure AWS credentials using SSH Terminal on your local desktop
```
# Configure AWS Credentials in command line
$ aws configure
AWS Access Key ID [None]: AKIASUF7DEFKSIAWMZ7K
AWS Secret Access Key [None]: WL9G9Tl8lGm7w9t7B3NEDny1+w3N/K5F3HWtdFH/
Default region name [None]: us-east-1
Default output format [None]: json

# Verify if we are able list S3 buckets
aws s3 ls
```
- Verify the AWS Credentials Profile
```
cat $HOME/.aws/credentials 
```
