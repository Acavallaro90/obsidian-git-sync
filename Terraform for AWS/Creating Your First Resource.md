- Start by declaring a provider
	- AWS
- Tell Terraform what region of AWS will this resource be deployed in
	- us-east-1
- Declare your resource(s)
	- resource "resource_type" "resource_name"
		- Details about the resource goes inside
- Example
		provider "aws" {
			region = "us-east-1"
		}

		resource "aws_vpc" "Terraform_VPC" {
			cidr_block = "10.0.0.0/16"
		}