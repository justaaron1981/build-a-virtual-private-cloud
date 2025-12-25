<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Virtual Private Cloud

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-networks-vpc)

**Author:** Aaron  
**Email:** Justaaron1981@yahoo.com

---

## Build a Virtual Private Cloud (VPC)

![Image](http://learn.nextwork.org/gleeful_red_proud_durian/uploads/aws-networks-vpc_2facf927)

---

## Introducing Today's Project!

### What is Amazon VPC?

Allows you to create a logically isolated virtual network within AWS, giving you control over your virtual networking environment. This is useful for security, isolating resources, and managing network traffic. 

### How I used Amazon VPC in this project

to create a secure and isolated virtual network for the application and its resources.

### One thing I didn't expect in this project was...

I didn't expect to learn that resources with in the VPC could be used to connect to the internet.

### This project took me...

one hour

---

## Virtual Private Clouds (VPCs)

a logically isolated section of a public cloud where users can run their applications and store data, while maintaining control over their virtual networking environment

There was already a default VPC in my account ever since my AWS account was created. This is because it's designed to simplify the initial setup of your AWS resources

a way of representing a range of IP addresses using CIDR notation, which includes the network address and the number of bits in the network prefix

![Image](http://learn.nextwork.org/gleeful_red_proud_durian/uploads/aws-networks-vpc_2facf927)

---

## Subnets

SUbnets are a logical subdivision of a larger network, often an IP network There are already subnets existing in my account, new AWS account to have subnets already set up

Once I created my subnet, I enabled auto-assign IPv4 address. This setting makes sure any EC2 instance launched in that subnet will instantly get a public IP address so that you won't have to create one manually.

The difference between public and private subnets are public subnets have direct internet access, allowing resources within them to be reached from outside the network, while private subnets do not

![Image](http://learn.nextwork.org/gleeful_red_proud_durian/uploads/aws-networks-vpc_157c4219)

---

## Internet gateways

internet gateways are a component that facilitates communication between a network (like a Virtual Private Cloud or VPC) and the public internet.

Attaching an internet gateway to a VPCmeans allowing 
resources within the VPC to communicate with the internet. 

If i missed this step my VPC would not conect to resources within the VPC, particularly those in public subnets, won't be able to directly connect to the internet. 

![Image](http://learn.nextwork.org/gleeful_red_proud_durian/uploads/aws-networks-vpc_4ae90410)

---

## Using the AWS CLI

---

---
