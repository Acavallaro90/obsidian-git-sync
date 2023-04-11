- Purchasing Options
	- On-Demand Instances
		- Short workload
		- Predictable pricing
		- Pay by second
	- Reserved (1 and 3 years)
		- Reserved Instances: long workloads
		- Convertible Reserved Instances: long workloads with flexible instances
	- Savings Plans (1 and 3 years)
		- Commitment to an amount of usage
		- Long workload
	- Spot Instances
		- Short workloads
		- Cheap
		- Can lose instances (less reliable)
	- Dedicated Hosts
		- Book an entire physical sever
		- Control instance placement
	- Dedicated Instances
		- No other customers will share your hardware
	- Capacity Reservations
		- Reserve capacity in a specified AZ (Availability Zone) for any duration
- EC2 On-Demand
	- Pay for what you use
		- Linux or Windows
			- Billing per second after the first minute
		- All other Operating Systems
			- Billing per hour
		- Has the highest cost but no up front payment
		- No long-term commitment
		- Recommended for short-term and un-interrupted workloads where you cannot predict how the application will behave
- EC2 Reserved Instances
	- Up to 72% discount compared to On-Demand
	- You reserve a specific instance attributes
		- Instance Type
		- Region
		- Tenancy
		- Operating System
	- Reservation period
		- 1 year (+discount)
		- 3 years (+++discount)
	- Payment options
		- No up front (+discount)
		- Partial up front (++discount)
		- All up front (+++discount)
	- Reserved instances scope
		- Regional or Zonal (reserve capacity in an AZ)
	- Recommended for steady-state usage applications (think database)
	- You can buy and sell in the Reserved Instance Marketplace
- EC2 Convertible Reserved Instances
	- Can change the following for the EC2 instance
		- Instance type
		- Instance family
		- Operating System
		- Scope
		- Tenancy
	- Up to 66% discount
- EC2 Savings Plan
	- Get a discount based on long-term usage (up to 72% discount)
	- Commit to a certain type of usage (10/hour for 1 or 3 years)
	- Locked to a specified instance family and AWS region
		- M5 in us-east-1 for example
	- Flexible across the following
		- Instance size (m5.2xlarge or m5.xlarge)
		- Operating System
		- Tenancy
- EC2 Spot Instances
	- Can get a discount of up to 90% compared to On-Demand
	- Instances that you "lose" at any point of time if your max price is less than the current spot price
	- The most cost-efficient instances in AWS
	- Useful for workloads that are resilient to failure
		- Batch jobs
		- Data analysis
		- Image processing
		- Any distributed workloads
		- Workloads with a flexible start and end time
	- Not useful for critical jobs or databases
- EC2 Dedicated Hosts
	- A physical server with EC2 instance capacity fully dedicated to your use
	- Allows you to address compliance requirements and use your existing server-bound software licenses
	- Purchasing options
		- On-Demand
		- Reserved
	- The most expensive option
	- Useful for software that have complicated licensing models or for companies that have strong regulatory or compliance needs
- EC2 Dedicated Instances
	- Instances that run on hardware that is dedicated to you
	- May share hardware with other instances in same account
	- No control over instance placement
		- Can move hardware after Stop/Start
![[Pasted image 20230410160741.png]]
- EC2 Capacity Reservations
	- Reserve On-Demand instances capacity in a specified AZ for any duration
	- You always have access to EC2 capacity when you need it
	- No time commitment (create/cancel anytime)
		- No billing discounts
	- Combine with Regional Reserved Instances and Savings Plans to benefit from billing discounts
	- Charge at On-Demand rate whenther you run instances or not
	- Suitable for short-term, uninterrupted workloads that needs to be in a specific AZ
![[Pasted image 20230410161329.png]]