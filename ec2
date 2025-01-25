provider "aws" {
  region = "us-east-1"
}

resource "aws_instance" "example" {
  ami           = "ami-04b4f1a9cf54c11d0" # Example AMI for Amazon Linux 2
  instance_type = "t2.micro"

  tags = {
    Name = "ExampleInstance"
  }
}
