# Hello World Node js application

## Tasks:

Deploy a Rest Application on AWS ECS Fargate Using Terraform.

The ECS Fargate should be deployed on Private Subenet.
Image should be read from ECR.
Create a GitHub workflow to run Terraform code

- we need teraform web account which must be put in provider.tf

- store token of terraform and aws secret in github secret vault in the same repo


### List of created resources
VPC:

Public Subnets
Private Subnets
Internet Gateway
NAT Gateway
Route Tables
Security Groups
Elastic Container Registry
ECS Cluster
