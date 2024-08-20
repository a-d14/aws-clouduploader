# CloudUploader

CloudUploader is a CLI tool that allows you to upload a file from your local system to an S3 bucket with one simple command.

## Installation and Setup
Before you download this you need a have an AWS account and need to set up the IAM Identity Center. 
Follow this link for instructions - https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html 

Next, define two environment variables namely, 
```bash
AWS_PROFILE # this variable contains the AWS profile name you will use to login
AWS_DEFAULT_PATH # in case no target directory is mentioned, the file will be copied to this folder
```
Depending on what shell you are using, you will have to define these variables in different files. Find out which using this command:
```bash
ps -p $$ 
```

## Usage

`cd` into the clouduploader folder, and run the following command:
```bash
./script <source_path> <destination_path>
```
