- A declarative way of outlining your AWS infrastructure, for any resource
	- Most of them are supported
- Example:
	- Within a CloudFormation template, you can declare
		- I want a Security Group
		- I want two EC2 Instances using this Security Group
		- I want an S3 Bucket
		- I want an Application Load Balancer in front of the EC2 Instances
	- CloudFormation creates these for you, in the correct order, with the exact configuration that you specified
- Benefits
	- Infrastructure as code
		- No resources are manually created
		- Excellent for control
		- Changes to the infrastructure are reviewed through code
	- Cost
		- Each resource within the stack is tagged with an identifier so you can easily see how much a stack costs you
		- You can estimate the costs of your resources using the CloudFormation template
		- Savings strategy
			- You can auto delete all resources at a specific time for a dev environment and then spin them all back up the following morning to be ready for use
	- Productivity
		- Ability to destroy and re-create an infrastructure on the cloud on the fly
		- Automated generation of diagram for your templates
		- Declarative programming (no need to figure out ordering and orchestration)
	- Don't re-invent the wheel
		- Leverage existing templates on the web
		- Leverage the documentation
	- Supports (almost) all AWS resources
		- Everything we'll see in this course is supported 
		- You can use "custom resources" for resources that are not supported