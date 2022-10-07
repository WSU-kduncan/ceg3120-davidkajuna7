# Part 1
## VPC
- Kajuna-VPC
- 10.0.0.0/24
- a private part of AWS that allows you to use AWS resources.

![VPC](Images\Screenshot 2022-10-04 214443.png)

## Subnet
- Kajuna-subnet
- 10.0.0.0/28
- range of IP addresses in Kajuna-VPC

![Subnet](Project2/Images/Screenshot 2022-10-04 214954.png)

## Internet Gateway
- Kajuna-Gateway
- Allows to communicate to public internet

![Internet Gateway](Images/Screenshot 2022-10-05 235258.png)

## Route Table
- Kajuna-route
- set of rules to determine network traffic

![Route](Images/Screenshot 2022-10-06 000654.png)

## Security Group
- Kajuna-SecurityGroup
- controls traffic for VPC instance

![Security Group](Images/Screenshot 2022-10-06 215708.png)

# Part 2
1. Ubuntu AMI
	- t2.micro
2. Connect VPC thouth Network settings
3. Auto-assign IP address b/c it removes stress of keeping track.
4. Create and attach storage volume through making of instance.
5. Tag instance while creating instance.
6. Associate VPC security group with instance by adding rules for traffic.
7.Allocate and associate elastic IP address.

![Instance](Images/Screenshot 2022-10-06 025849.png)

9. sudo hostnamectl set-hostname Kajuna-AMI

![SSH](Images/Screenshot 2022-10-06 025430.png)
