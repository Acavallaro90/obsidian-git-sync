- What is Microsoft Active Directory?
	- Found on any Windows server with AD Domain Services
	- Database of objects
		- User accounts
		- Computers
		- Printers
		- File Shares
		- Security Groups
	- Centralized security management
	- Create accounts
	- Assign permissions
- AWS Directory Services
	- AWS Managed Microsoft Active Directory
		- Create your own active directory in AWS
		- Manage users locally
		- Supports MFA
		- Establish "trust" connections with your on-premise active directory
	- Active Directory Connector
		- Directory Gateway (proxy) to redirect to on-premises active directory
		- Supports MFA
		- Users are managed on the on-premises active directory
	- Simple Active Directory
		- Active directory managed on AWS
		- Cannot be joined with on-premises active directory
		- Stand-alone active directory on AWS