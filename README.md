# Deploying a Web Page Inside a Custom VPC

## Objective

The objective of this project is to set up a custom Virtual Private Cloud (VPC) in AWS, configure public and private subnets, and deploy a web page using an EC2 instance within the public subnet. This project demonstrates skills in VPC creation, subnet configuration, internet gateway setup, route table management, and EC2 instance deployment.

### Skills Learned

- VPC Configuration: Setting up a custom VPC and configuring subnets.
- Subnet Management: Creating and managing public and private subnets.
- Internet Gateway Configuration: Attaching and configuring an internet gateway for internet access.
- Route Table Management: Creating and associating route tables with subnets.
- Security Groups: Configuring security groups to manage inbound traffic.
- EC2 Deployment: Launching an EC2 instance and deploying a web page.


### Tools Used

- Amazon VPC: For creating and managing the virtual private cloud and subnets.
- Amazon EC2: For launching and managing virtual servers.
- Amazon S3: For storing files (in this case, if needed for static web hosting).
- AWS Management Console: For configuring and managing all AWS resources.



### Outcome
This project successfully sets up a custom VPC with public and private subnets and deploys a web page using an EC2 instance in the public subnet. It showcases advanced skills in AWS VPC configuration, subnet management, internet gateway setup, and EC2 deployment.

## Steps

Create a custom VPC

<img width="1171" alt="Screenshot 2024-05-25 at 9 18 10 AM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/d1e27d3d-526e-4bc1-9e82-b17aa9a27de9">

Create both public and private subnets

<img width="1192" alt="Screenshot 2024-05-25 at 9 19 30 AM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/ebb29b4d-7cfd-4051-abc6-b01de98c87bc">


<img width="1193" alt="Screenshot 2024-05-25 at 9 20 04 AM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/c5f62931-3a36-4b54-a467-83c3d9903680">

Create IGW and attatch to VPC

<img width="1173" alt="Screenshot 2024-05-25 at 9 21 49 AM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/f3c94b95-2cd1-408d-a26f-8514eb114313">

Create and configure route tables

<img width="1190" alt="Screenshot 2024-05-25 at 9 23 03 AM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/2c59f4ad-5657-4888-90f1-fbdfc3992f56">

<img width="1383" alt="Screenshot 2024-05-25 at 9 25 42 AM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/d723208c-8bd8-40c5-a266-56aa050c2268">

Create security group for ec2 instance

<img width="1194" alt="Screenshot 2024-05-25 at 9 27 22 AM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/2364080c-4520-48ab-95a5-68f0b4e13bb4">

Launch EC2 inside public subnet

<img width="776" alt="Screenshot 2024-05-25 at 9 29 27 AM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/1c29add8-71f4-4522-bc53-4fd2477263be">

Verify EC2

<img width="1229" alt="Screenshot 2024-05-25 at 9 30 58 AM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/5d2eea1e-fa33-4a8e-b9c6-2af4f641a75b">

Test Traffic

<img width="671" alt="Screenshot 2024-05-25 at 4 47 09 PM" src="https://github.com/Hunter102002/Deploying-a-web-page-inside-a-custom-VPC/assets/98543129/138dc96a-8e84-44a6-8e83-758e5ec0e50a">


