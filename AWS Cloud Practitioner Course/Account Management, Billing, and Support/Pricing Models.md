- AWS has four pricing models
	- Pay as you go
		- Pay for what you use
		- Remain agile
		- Responsive
		- Meet scale demands
	- Save when you reserve
		- Minimize risks
		- Predictably manage budgets
		- Comply with long-term requirements
			- Reservations are available for
				- EC2 Reserved Instances
				- DynamoDB Reserved Capacity
				- ElastiCache Reserved Nodes
				- RDS Reserved Instance
				- Redshit Reserved Nodes
	- Pay less by using more
		- Volume-based discounts
	- Pay less as AWS grows
- Free services and free tier
	- IAM (free)
	- VPC (free)
	- Consolidated Billing (free)
	- Elastic Beanstalk (free but you pay for the resources created)
	- CloudFormation (free but you pay for the resources created)
	- Auto Scaling Groups (free but you pay for the resources created)
	- Free tier: https://aws.amazon.com/free
		- Always free
			- 25 GB of storage with DynamoDB
			- 1 million requests per month with Lambda
			- 1 million publishes with SNS
			- 10 custom metrics for CloudWatch
			- Etc.
- EC2 pricing
	- On-demand EC2 instances
		- Only charged for what you use
		- Minimum billing time of 60 seconds
		- Pay per second for Linux/Windows
		- Pay per hour for other Operating Systems
		- Number of instances
		- Instance configuration
			- Physical capacity
			- Region
			- Operating System
			- Software
			- Instance type
			- Instance size
		- ELB running time and amount of data processed
		- Detailed monitoring
			- Setting monitoring to 1 minute instead of 5 minutes for CloudWatch
	- Reserved instances
		- Up to 75% discount compared to on-demand on hourly rate
		- 1 or 3 year commitment required
		- More discounts if you pay early
			- All up front
			- Partial up front
			- No up front
	- Spot instances
		- Up to 90% discount compared to on-demand hourly rate
		- Bid for unused capacity
	- Dedicated hosts
		- On-demand
		- Reservation for 1 or 3 year commitment
	- Savings plan
		- An alternative to save on sustained usage
- Lambda pricing
	- Pay per API call
	- Pay per duration
- ECS pricing
	- EC2 launch type model
		- No additional fees
		- You pay for the AWS resources stored and created in your application
- Fargate pricing
	- Fargate launch type model
		- Pay for vCPU and memory resources allocated to your applications in your containers
- Storage pricing
	- S3
		- Pay per number and size of objects
			- Price can be tiered based on volume
		- Pay per number and type of requests
		- Data transfer out of S3 region
		- S3 transfer acceleration
		- Lifecycletransitions
	- EFS
		- Similar to S3
		- Pay per use
	- EBS
		- Pay per volume type
		- Pay for storage volume in per month provisioned
		- Snapshots
			- Added data cost per GB per month
		- Data transfer out are tiered for volume discounts
- Database pricing
	- RDS
		- Per hour billing
- Network pricing
	- Pay .01 for traffic for private IP
	- Pay .02 for traffic for public IP
		- Between AZs
- If you have 1 AZ, it is cheaper but you get rid of high availability