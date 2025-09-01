# VPC-study
VPC-study

## For VPC peering you need to just create a peering connection.

## For Bastion Host you need to create one public vpc and one private vpc.

## In public vpc you need to create one public subnet one ec2 instance with public ip also you need to create 
## a one internet gateway and to connect to public vpc.


## In private vpc you need to create one private subnet, one ec2 instance.(For internet access to private subnet you need to create a NAT gateway).
## When createtion of NAT gateway all settings configured with public vpc.Not private.

## In private gateway -
<img width="1901" height="401" alt="image" src="https://github.com/user-attachments/assets/e65109fe-66e4-437d-a54c-f4e05bd7b754" />

## Then you can ping google.com from private network.(Without NAT gateway you cant access)

