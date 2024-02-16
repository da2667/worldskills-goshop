# GO Shop Infrastructure

## What is this package?

This package contains the AWS CloudFormation template for the GoShop Web Application. This will deploy a:

- VPC
- EC2 Instance
- Security Groups
- RDS Instance
- etc ...

## How to run

In order to run (via the CLI) run this command:

``` aws cloudformation deploy --stack-name <stack-name> --template-file .\main.yml --parameter-overrides KeyName=<your-key-name> DBSubnetGroupNameTagValue=<insert_here> DBPass=<password_for_database> ```

This will deploy the neccessary infrastructure.

