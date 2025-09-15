
Class 7: EC2 Basics

Task: Build an Amazon Linux EC2 with a startup script.

Template: https://github.com/kirk-devsecops/bmc5/blob/main/ec2scrpit

Steps

Create NEW security group. DO NOT USE DEFAULT!
Create EC2
Copy public DNS. Using a note taking app, add “http://“ as a prefix to make it a useable link. Then, paste the link to the chat.
Notes:

Key pair connects a user’s computer to the AWS EC2 via secure shell (SSH).
Make sure to type http:// before any links are made
example: http://ec2-98-84-105-169.compute-1.amazonaws.com
tags are useful for organizational purpposes, as well as tracking resource usage across the orgnaization, essential for the office!
ALWAYS TAG RESOURCES!

Terminate the EC2 Instance

Navigate to EC2 → Instances
Select your instance
Instance State → Terminate Instance
Delete Security Group (Optional)

Navigate to EC2 → Security Groups
Select your created security group
Actions → Delete Security Group
Note: Can only delete after instance termination
