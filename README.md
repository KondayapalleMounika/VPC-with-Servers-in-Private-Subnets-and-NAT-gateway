# VPC-with-Servers-in-Private-Subnets-and-NAT-gateway

#About the Project.

Here, VPC is Created in two availabilty zones where each zone consists of one public subnet and one private subnet. And each public subnet contains NAT gateway and loadbalancer.Each Private subnet contains one server which are launched and terminated by Auto scaling group and receives traffic from load balancer. here, servers can connect to the internet by using NAT gateway.

#Things Done:

1. Created VPC in two availability zones where each zone consists of one public and private subnets. And also to improve resilency , created two NAT gateways in each public subnet of two availability Zones.

2. Created servers in private subnets by using Auto Scaling Group.

3. Created Bastion-host server in public subnet in order to connect to servers which are deployed in private subnets.

4. Deployed  Application in servers which are in private subnets.

5. Created Application Load Balancer in public subnets.


   
![vpc-example-private-subnets](https://github.com/user-attachments/assets/43cec7a1-d6bd-4de3-b2a8-ca0e19c7fe9c)
