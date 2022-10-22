
# Documentation For Linux and Windows Virtual Machine running Unix Server.

## This can be created with an account from a cloud service, using either:
a. Aws account(free tier)

b. Microsoft Azure (available for few months)

c. GCP account 


## Linux_Machine 

1. Launching your EC2 instance

2. Name your EC2 instance

3. Choose an AMI

4. Configure a key pair

5. Configure the network settings
  You use this pane to configure networking settings.
  The virtual private cloud (VPC) indicates which VPC you want to launch the instance into. You can have multiple VPCs, including different ones for development, testing, and production.
 
  In the Network settings section, choose Edit.
  From the VPC - required dropdown list, choose Lab VPC.
  The Lab VPC was created using an AWS CloudFormation template during the setup process of your lab. This VPC includes two public subnets in two different Availability Zones.

Using the Public ip address  you should be able to access the Web page from any browser of your choice


### Access the Machine with the IP Address  http://54.172.180.154/
![Screenshot from 2022-10-22 07-58-04](https://user-images.githubusercontent.com/44731076/197325298-22ec7e13-7445-4779-8ddf-d2f8fad6f9f4.png)