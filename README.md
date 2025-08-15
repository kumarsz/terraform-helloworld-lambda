
This is a terraform hello project to deploy lambda


----
Install terraform

# Install HashiCorp GPG key and repo
sudo yum install -y yum-utils

sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo

# Install Terraform
sudo yum install -y terraform

# Verify installation
terraform -version

----

Connecting to aws

aws configure

aws sts get-caller-identity



----

commands to be used

cd to this folder

terraform init

terraform plan

terraform apply# terraform-helloworld-lambda


----

aws lambda invoke --function-name terraform_hello_lambda output.json
cat output.json


