# Creating an EC2 Instance on AWS

Follow the steps below to launch an EC2 instance on AWS:

### 1. Launch the Instance
- Navigate to the **Launch Instance** option on your AWS Management Console.

  ![image](https://github.com/user-attachments/assets/ab4f7ffc-f9ea-4f9d-8389-82db4a57627c)

### 2. Enter the Instance Name
- Choose a name for your instance to identify it easily.

### 3. Choose an OS
- Under the **Quick Start** tab, select **Ubuntu Server 24.04 LTS 64bit**.

  ![image](https://github.com/user-attachments/assets/925ccb16-6f3c-4818-9f42-f400cc4b6541)

### 4. Select Instance Type
- Choose the **t2.medium** instance type (2 CPU cores, 4 GB memory). Alternatively, you can select **t2.micro** for smaller workloads.

### 5. Select Key Pair
- Choose an existing key pair or click on **Create new key pair**. Once created, a **.pem** private key file will be automatically downloaded. This file is essential for SSH access to your EC2 instance.

### 6. Configure Network & Security Group
- Leave the network settings as default.
- Select **Create security group**. Security groups act as a firewall to control inbound traffic. Ensure the necessary ports are opened to allow communication with your instance.

  ![image](https://github.com/user-attachments/assets/50502ed7-d2c1-47f7-ad13-39d4811f1db4)

### 7. Configure Storage
- The default storage configuration is **8GB**. You can adjust the size or add additional volumes based on your requirements.

### 8. Launch the Instance
- Once all configurations are complete, click on the **Launch Instance** button to create your EC2 instance.

### 9. Instance Created
- The EC2 instance gets created.
  
  ![image](https://github.com/user-attachments/assets/ffb20353-5e7d-4c5a-8629-dfb323bc4ad0)

### 10. Terminate the Instance
- Once done with the use, Terminate the Instance by selecting the instance name and then clicking on **Terminate (delete) Instance** under **Instance state** dropdown menu.


