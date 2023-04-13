- EBS volumes
	- Network drives that are attached to a single EC2 instance at a time
	- Mapped to a single Availability Zone
		- Can use EBS Snapshots for backups/transferring EBS volumes across Availability Zones
- AMI
	- Create ready-to-use EC2 Instances with our customizations and software installed
- EC2 Image Builder
	- Automatically build, test, and distribute AMIs
- ECS Instance Store
	- A high performance disk attached to our EC2 isntance
	- Data is lost if the instance is stopped or terminated
- EFS
	- Network file system that is attachable to many EC2 instances across many Availability Zones
- EFS-IA
	- Cost-optimized storage class for infrequently accessed files
	- A lifecycle policy determines the length of time needed to be moved to EFS-IA from EFS
- FSx for Windows
	- Network File System for Windows servers
- FSx for Lustre
	- High Performance Computing Linux file system