- Highly-securable, portable devices to collect and process data at the edge and migrate data into and out of AWS
- Use cases
	- Data migration
		- Snowcone
			- Small, portable computing
			- Rugged
			- Secure
			- Used anywhere
			- Withstands harsh environments
			- Light (4.5 pounds)
			- Device used for edge computing, storage and data transfer
			- Snowcone
				- 8 TB of HDD storage
			- Snowcone SSD
				- 14 TB of SSD storage
			- Use snowcone where snowball doesn't fit
			- Must provide your own battery/cables
			- Can be sent back to AWS offline or connect it to internet and use AWS DataSync to send data
		- Snowball Edge
			- Physical data transport solution
			- Move TBs or PBs of data in or out of AWS
			- Alternative to moving data over the network (and paying network fees)
			- Pay per data transfer job
			- Provide block storage and Amazon S3-compatible object storage
			- Snowball Edge Optimized
				- 80 TB of HDD capacity for block volume and S3 compatible object storage
			- Snowball Edge Compute Optimized
				- 42 TB of HDD or 28TB NVMe capacity for block volume and S3 compatible object storage
		- Snowmobile
			- A fucking truck
			- 1,000 PB
- For large amounts of data transfer, AWS will send you a device for you to transfer the data onto and then ship it back to them for them to put in S3 buckets