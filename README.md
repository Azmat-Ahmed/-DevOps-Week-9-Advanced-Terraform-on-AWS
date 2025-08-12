# DevOps Week 9: Advanced Terraform on AWS

Hello! I’m Azmat Ahmed, sharing my **Week 9** learning journey focused on mastering Terraform for AWS infrastructure automation.

## What I covered this week:

- Deep dive into Terraform workflows (`init`, `plan`, `apply`, `destroy`)
- Managing Terraform state remotely with **S3 buckets** and **DynamoDB** for locking
- Building modular Terraform code by splitting resources into separate `.tf` files (`ec2.tf`, `s3.tf`, `variables.tf`)
- Provisioning AWS resources: EC2 instances, S3 buckets, DynamoDB tables
- Practicing version control best practices by **excluding `.tfstate`** files from Git and using remote state
- Running Terraform CLI commands on Linux and troubleshooting deployment errors

## Project Structure

```plaintext
main.tf
variables.tf
ec2.tf
s3.tf
dynamodb.tf
outputs.tf
terraform.tfvars
Why use Terraform?
Terraform enables Infrastructure as Code (IaC), which makes infrastructure reproducible, consistent, and easy to manage.

Resources and tools used:
AWS (EC2, S3, DynamoDB)

Terraform CLI on Linux

Remote state with S3 + DynamoDB for locking

Connect with me:
Portfolio: https://azmatahmed.netlify.app

LinkedIn: https://www.linkedin.com/in/azmat-ahmed-13610a314/

Email: ahmedawan9519@gmail.com

Keywords: Terraform, AWS, Infrastructure as Code, EC2, S3, DynamoDB, DevOps, remote state, terraform best practices# -DevOps-Week-9-Advanced-Terraform-on-AWS
