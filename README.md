# Custom-AWS-VPC-with-Public-and-Private-Subnets

## Overview
Deployed a custom VPC on AWS across two Availability Zones with public and private subnet architecture.\

## Architecture
- VPC: vpc-ap-south-1-test (10.0.0.0/16)
- Region: ap-south-1 (Mumbai)
- Public Subnets: Public-1A (10.0.1.0/24), Public-1B (10.0.2.0/24)
- Private Subnets: Private-1A (10.0.3.0/24), Private-1B (10.0.4.0/24)
- Internet Gateway: Test-IGW
- Private Route Table: Private-RT (associated with Private-1A, Private-1B)

## What I learned
- How to design VPC CIDR ranges and subnet segmentation
- Difference between public and private routing
- How Internet Gateways and Route Tables control traffic flow
- Multi-AZ design for high availability
