# AWS Learning Journey - Amazon VPC

## Introduction
Today I have learned about Amazon VPC (Virtual Private Cloud). This is a service provided by AWS which helps you create an isolated virtual network in AWS.
This gives you control over your networking resources.

## What is Amazon VPC?
This enables us to launch AWS resources in a virtual, isolated network.
This gives you control over:
- IP Address Ranges
- Subnets
- Routing
- Internet
- Network Security

## Key Concepts

### VPC (Virtual Private Cloud)
A logically isolated network within AWS. Enables us to launch resources such as EC2 Instances.

### Subnets
A smaller portion of your VPC IP Address Range.
**Public Subnets:** Subnets that are able to route traffic to an Internet Gateway.
**Private Subnets:** Subnets that are unable to directly route traffic to an Internet Gateway.

### CIDR (Classless Inter-Domain Routing)
CIDR determines what IP Address range you have within your VPC/Subnets.
Example: `10.0.0.0/16`

### Internet Gateway (IGW)
Allows traffic to be sent between resources in your VPC and the internet if allowed via routing.

### Route Tables
Enables you to set rules to determine where your traffic goes.
This helps control traffic between subnets, internet etc.

### NAT Gateway
Allows resources within a private subnet to make outgoing connections to the internet.

### Network ACL (NACL)
Provides security at the subnet level. Controls traffic coming into and out of your subnets.
- Stateless.
- Allow/Deny Rules.

##Security Groups
These act as virtual firewalls. Can be added to AWS resources such as EC2 Instances.
- Stateful.
- Only Allow Rules.
- Controls traffic coming into and out of resources.

## Key Points
- VPC provides an isolated network.
- Subnets enable you to break your VPC down into smaller networks.
- Public and Private Subnets vary depending on routing.
- Internet Gateways provide internet access.
- Route Tables help control traffic.
- NAT Gateways provide internet access to private resources.
- Security Groups and NACLs provide network security.


---

Learning AWS, one service at a time!
