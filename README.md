# Work-links
https://altron.udemy.com/course/terraform-fast-track/learn/lecture/21522782#overview

provider "aws" {
    region = "eu-east-1"
}
resource "aws_vpc" "myvpc" {
    cidr_block = "10.0.0.0/16"
}
