# AWS
The AWS Certified Solutions Architect course has prepared me in the following areas:

- Hands-on experience using compute, networking, storage, and database AWS services
- Hands-on experience with AWS deployment and management services
- Ability to identify and define technical requirements for an AWS-based application
- Ability to identify which AWS services meet a given technical requirement
- Knowledge of recommended best practices for building secure and reliable applications on the AWS platform
- An understanding of the basic architectural principles of building on the AWS Cloud
- An understanding of the AWS global infrastructure
- An understanding of network technologies as they relate to AWS
- An understanding of security features and tools that AWS provides and how they relate to traditional services


AWS list of completed hands on activities

1) High Availability, Fault Tolerance, and Scalability - Implement Highly Available, Fault Tolerant, and Scalable Systems:
    Demonstrate the ability to implement a highly available cloud solution, Demonstrate the ability to design fault tolerance in the application, Demonstrate the ability to design scalable systems, Demonstrate the ability to create and use Amazon Machine Images (AMI),Demonstrate the ability to identify the proper scalable configuration, Demonstrate the ability to configure and use the proper instance sizes within the configuration, Demonstrate the ability to monitor systems based off of performance, Demonstrate ability to configure security groups

2) VPC and VPC Networking:

    Build and Configure Virtual Private Clouds (VPCs), Demonstrate the ability to create a VPC, Demonstrate the ability to identify and configure VPC/Subnet requirements

3) Configure Subnets and VPC Networking:

    Demonstrate the ability to identify and configure a NAT Gateway, Demonstrate the ability to identify and create public subnets,Demonstrate the ability to identify and create private subnets, Demonstrate the ability to configure subnet networking using given requirements

4) Introduction to AWS Identity and Access Management (IAM):

    Demonstrate the ability set up users and groups, and to protect your resources with access control policies. Also how to connect to other identity services to grant external users access to your AWS resources.

5) Introduction to VPC:

    This lab will walk you through the primary components of the VPC so you can understand how they work together to create secure AWS environments. You will create public and private subnets and learn the differences between them.

6) Building a Three Tier Network VPC From Scratch in AWS:

    Hands-on experience building and connecting the following components inside AWS:
VPC's, Subnets, Internet Gateway, Route Tables, Nat Gateway, Network Access Control Lists (NACLs). These components are the foundation of highly available/fault tolerant networking architecture inside of AWS, and cover concetps such as infrastrucutre, design, routing, and security.

7) Creating and Testing a Peering Connection with a Private VPC:

    Gained knowledge and experience with: Creating a VPC, Creating a VPC peering connection, Editing route tables for the peering  connection,Launching EC2 instances in each VPC, Testing the connection over SSH using private IP addresses

8) Security Groups and Network ACLs:

    Security Groups and Network ACLs are the foundation of security in any AWS environment. Understanding the differences between them and the use cases for which they are best suited is crucial to ensuring your environment is as secure as possible to prevent attackers and other malicious actors from compromising your information,walk through the differences between Security Groups and NACL.

9) Creating a NAT Gateway in AWS:

    Demonstrate how to set up a NAT Gateway to allow an EC2 instance in a private subnet to access the Internet.

10) Introduction to EC2:

    AWS EC2 is one of the core services of the AWS ecosystem that you absolutely must know to be successful in a cloud-related career. Even if your app doesn't run on EC2, utilizing EC2 instances for development and to perform other tasks is critical to a well-architected AWS solution. In this learning activity, we are going to create an EC2 instance, create and customize a security group to allow access, and createa key pair in order to ensure our access is secure.

11) Creating EC2 Amazon Machine Images (AMIs):

    The ability to create a copy of your Amazon Machine Image (AMI) with just a few clicks of the mouse or a few commands in the API is excellent for ensuring your application is always able to be restored at a moment's notice. This also allows you to deploy mirrored servers in other availability zones or even regions if you copy them over. In this learning activity, we will deploy software to a machine and illustrate how AMIs can be used to distribute that image among your environment.

12) Preparing an Instance for a Custom AMI:

    The AWS EC2 service is outstanding when it comes to hosting applications quickly and efficiently. Part of what makes EC2 so efficient is the Amazon Machine Images, or AMIs. These images allow you to spin up EC2 instances at a moment's notice. These AMIs are great, but you have to guard them very closely if there is any sensitive information on them. If an AMI were accidentally shared to the wrong account, this information would go with it. That's why you must remove any sensitive information from EC2 instances before creating AMIs from them. This learning activity will show you how to remove sensitive information from your EC2 instances before creating an AMI to maintain utmost security.

13) Working with EBS:

    EBS (Elastic Block Store) volumes are an important concept to understand when learning how to manage your EC2 instances. Amazon Elastic Block Store (Amazon EBS) provides persistent block storage volumes for use with Amazon EC2 instances in the AWS Cloud. Each Amazon EBS volume is automatically replicated within its Availability Zone to protect you from component failure, offering high availability and durability. In this activity, we will walk through adding an EBS volume to an EC2 instance and then mount it, so the student will have a grasp of the process going forward.

14) Auto Scaling and High Availability:

    EC2 is a great platform for hosting websites and web apps, but what happens when the app becomes too popular for your existing instance? Obviously, it can be replaced by a larger instance, but what if the demand is variable? That's where autoscaling comes in! With autoscaling, your app can be scaled out with extra servers to split the load until it decreases. Once the load decreases, your app can return to the normal number of servers and your app won't be left with an abundance of excess, and expensive, resources. The app will also benefit from more servers to receive requests if one or more of the other servers fail. This is high availability and is crucial in web apps of today. This Learning Activity will walk you through configuring autoscaling and high availability in order to teach the important methods to maintaining a dynamic and resilient app

15) Getting Started With Windows Server On Amazon EC2:

    Launching our first Windows EC2 instance on Amazon Web Services. This learning activity will focus on the basic concepts of EC2 as well as using automation and powershell to "bootstrap" a web server. We'll learn about elastic IP addresses, security groups, and connecting to the Windows 2012 R2 EC2 instance.

16) Shared Responsibility Model:

    Security and compliance is a shared responsibility between AWS and the customer. This shared model helps relieve your operational burden as AWS operates, manages, and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates. AWS is responsible for protecting the infrastructure that runs all services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services.
    
The Customer responsibility and management of the following: 

    The security configuration of the data plane, including the configuration of the security groups that allow traffic to pass from the Amazon EKS control plane into the customer VPC. The configuration of the worker nodes and the containers themselves. The worker node guest operating system (including updates and security patches). Other associated application software: Setting up and managing network controls, such as firewall rules. Managing platform-level identity and access management, either with or in addition to IAM
