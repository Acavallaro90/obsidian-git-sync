- Under EC2, select Volumes on left-hand side under Elastic Block Store
- Select Create Volume
- Select the volume type and size and assign to an availability zone
- Select Create Volume
- Wait for your new volume to say Available
- Click on your new volume and select Actions drop down menu
- Choose Attach Volume
- Choose the EC2 instance to attach the volume to
- You can have multiple volumes attached to a single EC2 instance but a EBS volume can only be assigned to a single EC2 instance
- You can also detach and delete the volumes in the same page