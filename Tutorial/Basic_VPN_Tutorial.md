# Basic VPN Setup Tutorial   
## **Part 1**: Get a free AWS EC2 to run the VPN service  

1. Sign up for a new AWS account to get the free tier. Just follow AWS guide.  

    **Note**: You need a credit or debit card when you sign up.

    > - This is the [sign up page](https://portal.aws.amazon.com/billing/signup#/start/email "Sign up your account").  

    > - This is the [AWS Free Tier](https://aws.amazon.com/cn/free "Learn about the free tier").  
  
2. Now you already have an AWS account. We can start create EC2 server.

    1. Sign in your account [here](https://aws.amazon.com/cn/console/).  

    2. Choose a region where you want to deploy the server.  
    ![Image](./Images/choose_region.png)

    3. Go to EC2 service.  
    ![Image](./Images/goto_EC2.png)

    4. Launch a new instance.
    ![Image](./Images/Launch_instance.png)

    **Note: Be careful from here and keep an eye on whether the service you choose is included in the free tier.**  

    5. Set the name for your instance and choose an AMI.
    ![Image](./Images/choose_AMI.png)

    6. Select free instance type and create new key pair, about the network settings, choose create security group.
    ![Image](./Images/Instance_type.png)

    7. Configure storage to 30GB, this is in the free tier.
    ![Image](./Images/Configure_storage.png)

    8. Click the Launch instance button to get your own free EC2 instance.