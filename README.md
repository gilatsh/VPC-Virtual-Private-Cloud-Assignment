# VPC-Virtual-Private-Cloud-Assignment
The task requires the creation of a VPC with multiple subnets, routing tables, and gateways. Additionally, two EC2 instances will be launched, one with a MySQL server installed and another with only SSH public access. Relevant security groups must also be created to secure the infrastructure.

The task also involves verifying that the MySQL server is accessible by the SQL client and can "talk" with the server both locally and remotely. 
* Bonus step: Automate the MySQL service installation on a public ec2.

Overall, this task aims to demonstrate an understanding of how to set up a secure and functional VPC with multiple subnets, gateways, and EC2 instances, as well as proficiency in configuring a MySQL server and using SQL clients to interact with it.

The assignment:
1. Create VPC
2. Add 4 subnets into it, in 2 different availability zones (2 in each AZ).
a. 2 private
b. 2 public
c. 2 routing tables, 1 public and 1 private, and assigned to respective subnets.
d. Create an internet gateway and attach it to a public subnet.
e. create NAT gateway attach it to private subnet.
3. Add two servers:
a. EC2 (Amazon Linux 2) with only SSH public access.
b. EC2 (Amazon Linux 2) with MySQL server.
4. Create relevant Security groups
5. Verify that after connecting to ec2 using ssh, and operating the SQL client, we can “talk” with the MySQL server.

Bonus step
Automate the MySQL service installation on each ec2.
