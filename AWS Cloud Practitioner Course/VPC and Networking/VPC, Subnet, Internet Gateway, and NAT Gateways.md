- VPC
	- Virtual Private Cloud
	- Private network to deploy your resources (regional resource)
- Subnets
	- Allow you to partition you network inside your VPC (Availabilty Zone resource)
	- A public subnet is a subnet that is accessible from the internet
	- A private subnet is a subnet that is not accessible from the internet
	- To define access to the internet and between subnets, we use Route Tables
![[Pasted image 20230411094516.png]]
- Internet Gateway
	- Helps our VPC instances connect with the internet
	- Public subnets have a route to the internet gateway
	- Private subnets will need to have NAT Gateways to access the internet
- NAT Gateway
	- AWS managed
- NAT Instances
	- Self managed
- NAT
	- Allow your instances in your private subnets to access the internet while remaining private
	- Create a NAT Gateway in our public subnet and create a route from the private subnet to the NAT Gateway and a route from the NAT Gateway to the Internet Gateway
- https://cidr.xyz/