# Step-by-Step Guide to Setting Up Terraform, AWS CLI, and Your AWS Environment

## Step 1: Install Terraform

1. Download terraform for Windows zip file and extracted the file  
2. Move `terraform.exe` to a directory  
3. Add the directory to system PATH i.e `C:\Program Files\terraform`  

```bash
terraform version

## Step 2: Install AWS CLI

I installed the AWS CLI

```bash
aws --version

## Step 3: Configure AWS CLI

I configured AWS CLI using my IAM user credentials.

Input the following credentials :
• AWS Access Key ID
• AWS Secret Access Key
• Default region: us-east-1
• Output format: json

```bash
aws configure list

## Step 4: Verify AWS Configuration

Using aws sts get-caller-identity

```bash
aws sts get-caller-identity

## Step 5: Set Up Visual Studio Code

I installed Visual Studio Code and added the following extensions:
• Terraform
• AWS Toolkit

## Conclusion

Setting up Terraform and AWS CLI is important in learning Infrastructure as Code. Despite initial challenges with environment variables, I was able to successfully configure my environment and connect all tools together. This setup now allows me to:

• Provision infrastructure using Terraform
• Manage AWS resources from the CLI
• Build real-world projects
