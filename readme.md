# terraform-aws-my-module

A Terraform module to deploy an AWS EC2 instance.

## Usage

```hcl
module "ec2_instance" {
  source        = "github.com/your-username/terraform-aws-my-module"
  ami           = "ami-12345678"
  instance_type = "t2.micro"
  name          = "MyInstance"
}
