# ami-lb-ssm-dynamic-sit
Hosting a Dynamic Website that involves AMI, LB and SSM
#### STEPS
1. Create IAM Role (S3 Full Access and Session Manager(SSM))
2. Create S3 Bucket and Upload Website Files
3. Create EC2 Instance and Remoting into Server Using Bash Script Code in Session Manager 
4. Copy the site link and view the site on Browser
#### Create AMI
5. Click on the Server (EC2 Instance) -> Click on Action -> Click Image Template -> Click Create Image
6. Enter Name and Description
#### Lunch Instance from AMI
7. Create Second Server (EC2 Instance)
8. Choose the Image to Use
9. Click on Lunch
10. Configure Instance
#### Create Load Balancer
11. Click on Load Balancer From the Left side
12. Configure: Internet Facing, Mark all the Subnet
13. Create Security Group (http and https)
14. Create Target Group -> Register Target
15. Select the two Servers (EC2 Instances)
#### For Confiremation Purpose, Significantly Differentiat the Two Servers Using Session Manager to Access the Sites and Edit each of the site code.

![ami-lb-ssm-dynamic-sit_1_role](https://user-images.githubusercontent.com/16262170/194515978-35ff369b-3828-4bc1-b878-f025f4591bf9.jpg)
![ami-lb-ssm-dynamic-sit_2](https://user-images.githubusercontent.com/16262170/194515998-e8a247bb-7708-4773-854d-60db058a112b.jpg)
![ami-lb-ssm-dynamic-sit_2-instance-1](https://user-images.githubusercontent.com/16262170/194516029-0c5b6ae2-0f6e-4100-a1ad-8fff1bfad1bd.jpg)
![ami-lb-ssm-dynamic-sit_2-instance-2](https://user-images.githubusercontent.com/16262170/194516043-31ead49c-f27c-4aac-b80b-7030c569a0fb.jpg)
![ami-lb-ssm-dynamic-sit_bash_script](https://user-images.githubusercontent.com/16262170/194516104-c898c609-8df7-48e1-9910-9a2ca10769df.jpg)
![ami-lb-ssm-dynamic-sit_image](https://user-images.githubusercontent.com/16262170/194516136-421e30be-57d4-4cdc-a9bf-b6393a8d3bda.jpg)
![ami-lb-ssm-dynamic-sit_lb](https://user-images.githubusercontent.com/16262170/194516157-06fbadab-0419-40b4-8dd4-3609c6aecd1c.jpg)
![ami-lb-ssm-dynamic-sit_server_1_1](https://user-images.githubusercontent.com/16262170/194516189-fb15a6ce-80c9-4cd5-985e-860ff58dbc85.jpg)
![ami-lb-ssm-dynamic-sit_server_2_2](https://user-images.githubusercontent.com/16262170/194516221-f7d937d7-1d6f-4bec-ba82-16176a03b24e.jpg)
