# 3tier_aws_terraform
Creating a 3-Tier Architecture on AWS via Terraform

## How It Works

I use terraform cloud to create 3-tir infrastructure.

Create following workspace variables in terraform cloud.

key                         value                      Category
namespace               my-3tier-terraform              terraform
region                   us-east-1                      terraform
AWS_ACCESS_KEY_ID        <access key id>                env
AWS_SECRET_ACESS_KEY        <secret acess key>.         env

execute from local terminal or from terraform cloud.

terraform init
terraform fmt
terraform plan
terraform apply
