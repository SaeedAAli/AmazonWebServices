## Assignment 2 - Application Load Balancer

On this assignment, the objective is being able to combine two ec2 instances behind a Application load balancer, by doing this it enables to focus on balancing, health checks and proper security group isolation.

Deploy two EC2 instances behind an ALB. The ALB must handle all incoming traffic. EC2 instances should not be accessible directly from the internet

##  What was required for this to work
1) an Application Load Balancer
2) VPC with two EC2 Instaces
3) Security Groups for both the Instances and ALB
4) Target Groups and Health Checks


Virutal Private Cloud
<img src="https://raw.githubusercontent.com/SaeedAAli/AmazonWebServices/refs/heads/main/Assignment/VPCAWS2.png" />


EC2 Instances & Security Groups
<img src="https://raw.githubusercontent.com/SaeedAAli/AmazonWebServices/refs/heads/main/Assignment/Aec2.png" alt="EC2 Assignment" />


<img src="https://raw.githubusercontent.com/SaeedAAli/AmazonWebServices/refs/heads/main/Assignment/SGS.png" alt="Security Groups" />

Target Groups & Application Load Balancer
<img src="https://raw.githubusercontent.com/SaeedAAli/AmazonWebServices/refs/heads/main/Assignment/targetgroups.png" alt="Target Groups" />

<img src="https://raw.githubusercontent.com/SaeedAAli/AmazonWebServices/refs/heads/main/Assignment/Screenshot%202026-03-10%20at%2019.41.11.png" alt="AWS Screenshot" />


Verify Check on Two Instances

<img src="https://raw.githubusercontent.com/SaeedAAli/AmazonWebServices/refs/heads/main/Assignment/firstinstance.png" alt="First Instance" />

<img src="https://raw.githubusercontent.com/SaeedAAli/AmazonWebServices/refs/heads/main/Assignment/finale.png" alt="AWS Architecture Diagram" />

