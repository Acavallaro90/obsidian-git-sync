- A managed DNS (Domain Name System)
- DNS
	- A collection of rules and records which helps clients understand how to reach a server through URLs
- In AWS, the most common records are
	- www.google.com -> 12.34.56.75 == A Record (IPv4)
		- Mapping the website to an IPv4 address is called an A Record
	- www.google.com -> 2001:0db8:85a3:0000:0000:8a2e:0370:7334 == AAAA (IPv6)
		- Mapping the website to an IPv6 address is called an AAAA Record
	- www.search.google.com -> www.google.com == CNAME (hostname to hostname)
		- Mapping one URL to another URL is called a CNAME Record
	- example.com -> AWS resource == Alias
		- Mapping a URL to an AWS resource is called an Alias record
- Routing policies
	- Simple routing policy
		- No health checks
	- Weighted routing policy
		- Assign weights to EC2 instances to get traffic distributed to them
			- A version of load balancing
	- Latency routing policy
		- Where traffic originates from will determine what server the user will use
			- Traffic from USA will use a region in USA
	- Failover routing policy
		- Health check on primary
		- Redirect to others if unhealthy
		- Disaster recovery