provider "aws" {
    region = "ap-south-1"
    }

    resource "aws instance" "foo"{
     ami             =   "ami-03f4878755434977f " #ap-northeast-3
     instance_type   =   "t2.micro"
  tags  = {   
     Name = "tf and jenkins"
      }
}      
