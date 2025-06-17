# Specify the AWS provider and region
provider "aws" {
  region = "us-east-1"
}

# Create an EC2 instance
resource "aws_instance" "example" {
  ami           = "ami-0123456789abcdef0"  # Replace with a valid AMI ID for your region
  instance_type = "t2.micro"               # Free-tier eligible instance type
