## Provision AWS EC2 instance using Terraform

### Steps to provision aws ec2 instance with terraform :

- Clone repository
```
git clone https://github.com/rizkypanz16/terraform-aws-ec2-single_instance.git
```
- Change the configuration in the main.tf file like: <access_key>, <secret_key>, <sg-id>, <subnet-id>, <keypair-name> according to the aws configuration you have made
- Plan - Preview changes before applying.
```
terraform plan
```
- Apply - Provision reproducible infrastructure.
```
terraform apply
```
