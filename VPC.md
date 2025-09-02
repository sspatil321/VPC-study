# VPC-study

===========================================================================================
# VPC Peering -

### For VPC peering you need to just create a peering connection.

===========================================================================================
# Bastion Host -

## For Bastion Host you need to create one public vpc and one private vpc.

## In public vpc you need to create one public subnet one ec2 instance with public ip also you need to create 
## a one internet gateway and to connect to public vpc.


## In private vpc you need to create one private subnet, one ec2 instance.(For internet access to private subnet you need to create a NAT gateway).
## When createtion of NAT gateway all settings configured with public vpc.Not private.

## In private gateway -
<img width="1901" height="401" alt="image" src="https://github.com/user-attachments/assets/e65109fe-66e4-437d-a54c-f4e05bd7b754" />

## Then you can ping google.com from private network.(Without NAT gateway you cant access)

============================================================================================

# Transit Gateway -

## AWS Transit Gateway is a networking service that connects thousands of Amazon VPCs and on-premises networks using a single gateway.
## It uses a hub-and-spoke model to route all traffic to and from each VPC or VPN, and provides one place to manage and monitor it all.

<img width="1284" height="767" alt="image" src="https://github.com/user-attachments/assets/b33bb6cf-075d-4bf8-8a49-815ddb347cad" />

<img width="1275" height="736" alt="image" src="https://github.com/user-attachments/assets/d6af173f-39dc-4fef-a81e-64e73ae6df60" />




