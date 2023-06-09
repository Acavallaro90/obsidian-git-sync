- High availability
	- Having your applications across multiple availability zones
- Scalability
	- Vertical
		- Increasing the size of your EC2 instances
	- Horizontal
		- Increasing the number of EC2 instances
- Elasticity
	- The ability to scale up and down based on demand
- Agility
	- The ability to create and delete resources very quickly
- Elastic Load Balancers (ELB)
	- Distribute traffic across backend EC2 instances
	- Can be multi-AZ
	- Supports health checks
	- Four types
		- Classic (retired in 2023)
			- Layer 4 and 7
		- Application
			- HTTP
			- HTTPS
			- gRPC
			- Layer 7
		- Network
			- High performance
			- TCP
			- Layer 4
		- Gateway
			- Additional security
			- Layer 3
- Auto Scaling Groups
	- Implement elasticity for your application across multiple AZ
	- Scale EC2 instances based on the demand on your system
	- Replace unhealthy EC2 instances
	- Integrated with ELB