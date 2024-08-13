# VPC-with-Servers-in-Private-Subnets-and-NAT-gateway

#About the Project.

Here, VPC is Created in two availabilty zones where each zone consists of one public subnet and one private subnet. And each public subnet contains NAT gateway and loadbalancer.Each Private subnet contains one server which are launched and terminated by Auto scaling group and receives traffic from load balancer. here, servers can connect to the internet by using NAT gateway.
