- Open PowerShell
- Write the following commands
	- ssh -i <path to the downloaded pem file from creating EC2 instance> ec2-user@<public IP address of the EC2 instance>
	- Example: ssh -i '.\EC2 Tutorial.pem' ec2-user@3.84.30.91
- Trust the connection
- If you get permission error, follow these steps
	- Navigate to .pem file where it was saved
	- Right click on it and choose Properties
	- Open Security tab
	- Select Advanced
	- Make sure you are the owner of the .pem
	- Disable Inheritance and remove all inherited permissions for this object
	- Select "Select a principal"
	- Enter your information
	- Give Full control and hit OK
- Rerun the ssh command above