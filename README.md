# SETTING UP INFRASTUCTURE ON AWS USING TERRAFORM

## I will create resouces like
1.Create vpc

2.Create internet gateway

3.Create custom route table  # determine where network traffic from your subnet or gateway is directed.

4.Create subnets

5.Associate subnet with route table

6.security group   # should  have inbound and outbound group. that is ingress and egress

7.s3 bucket

8.aws_s3_bucket_public_access_block to make it public

9.
I will place my access key and secretkey in the aws configure command because hard-coded credentials are not recommended in any Terraform configuration and risks secret leakage should this file ever be committed to a public version control system. 
