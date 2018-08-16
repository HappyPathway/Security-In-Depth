# Security-In-Depth

## Create Base permissions in Vault. 
This Module Binds Policy to GitHub Teams and configures an Admin User for base project.

https://github.com/HappyPathway/terraform-vault-project

## Create AWS SubAccount
This Module Creates an AWS SubAccount, configures AWS Dynamic Secrets Engine in Vault and makes AWS IAM Credentials Available for Terraform AWS Provider.

https://github.com/HappyPathway/terraform-aws-accounts.git


## Create RDS Instance with Vault Policies, using Dynamic AWS Credentials
This Repo features code that will all the terraform-aws-mysql-server module, passing in Dynamic AWS Credentials from Vault.
In this terraform-aws-mysql-server module, There are 2 roles (using Database Secrets Engine) that get configured in Vault to allow access to the provisioned database.

https://github.com/HappyPathway/aws-vault-mysql
