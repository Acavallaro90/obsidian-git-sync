- VPC Endpoints
	- Endpoints allow you to connect to AWS services using a private network instead of the public internet network
	- This gives enhanced security and lower latency to access AWS services
		- Lower latency is because you are bypassing network hubs
	- You can create a VPC Endpoint Gateway for AWS services to access an EC2 instance
		- VPC Enpoint Gateway is used for S3 and DynamoDB only
		- All other AWS services use a VPC Endpoint Interface