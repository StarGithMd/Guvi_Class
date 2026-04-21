### AWS Task-1 (EC2, AWS CLI, AMI)
- https://docs.google.com/document/d/1_ubEMSWcJS9qM5tJCQh7EWUymaIBADNAbTQ6WqagFEA/edit?usp=sharing

#### Techstacks needs to be used : 
- AWS EC2 (windows)
- RDP (Preavailable in Windows)

#### How do I submit my work?
- Push all your work files to GitHub (O/P screenshot images must).
- Submit your URLs in the portal.

#### Terms and Conditions?
- You agree to not share this confidential document with anyone. 
- You agree to open-source your code (it may even look good on your profile!). Do not mention our company’s name anywhere in the code.
- We will never use your source code under any circumstances for any commercial purposes; this is just a basic assessment task. 

- NOTE: Any violation of Terms and conditions is strictly prohibited. You are bound to adhere to it.


#### Task Description:
#### 01_Q. Create a windows Vm machine in AWS and connect with RDP open CMD in windows share the about system info.


***********************************************************************************************************************
#### Opened bash shell on my laptop and perfomed assigned task on it and pushed it on GitHub repository.
#### To complete the task activity, observed the following points and perform the suggested steps.
- [A] Created an ec2 instance with windows on AWS portal, Take access RDP and collect systeminfo logs

#### Log in to AWS Management Console
 - Go to the AWS Console (console.aws.amazon.com in Bing).
   - Navigate to EC2 Dashboard.
   - Start the Launch Wizard
   - Click Launch Instance.
   - Choose an Amazon Machine Image (AMI)

- Select a Windows Server AMI (e.g., Windows Server 2022 Base).
   - AWS provides several versions (2016, 2019, 2022).
   
- Choose Instance Type
   - Common choice: t2.micro (free tier eligible).
   - For heavier workloads, pick larger instance types.

- Configure Instance Details
   - Number of instances.
   - Network (VPC and subnet).
   - Assign a public IP if you want remote access.
   - IAM role (optional, for permissions).

- Add Storage
   - Default is 30 GB (can increase).
   - Choose SSD (gp3) or HDD depending on needs.
   
- Configure Security Group
   - Create or select a security group.
   - Add inbound rules:
   - RDP (TCP 3389) → allow from your IP for remote desktop access.
   - Other ports as needed (e.g., HTTP/HTTPS).

- Review and Launch
   - Click Launch.
   - Select or create a Key Pair (needed to decrypt the Windows admin password).
   - Download the key pair (.pem file) and keep it safe.
   - Connected to the Instance
   - Waited until the instance state is running.

- Select the instance → Connect → RDP Client.
   - Use the key pair to decrypt the Administrator password.

- Open the RDP file in Windows Remote Desktop, enter the decrypted password, and connect.
   - Collected systeminfo logs

******************************************************************************************************************************

- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git add .; git commit -m "03_Scripting_Task-"; git push origin main
   - [main 4b5661d] 03_Scripting_Task-
   - 3 files changed, 118 insertions(+)
   - create mode 100644 05_AWS_Task_1/AWS_Task.md
   - create mode 100644 05_AWS_Task_1/SnapShot_1.jpg
   - create mode 100644 05_AWS_Task_1/systeminfo_log.txt
   - Enumerating objects: 7, done.
   - Counting objects: 100% (7/7), done.
   - Delta compression using up to 8 threads
   - Compressing objects: 100% (6/6), done.
   - Writing objects: 100% (6/6), 2.34 MiB | 1.18 MiB/s, done.
   - Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
   - remote: Resolving deltas: 100% (1/1), completed with 1 local object.
   - To https://github.com/StarGithMd/Guvi_Class.git
     - bffee51..4b5661d  main -> main
- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git status
  - On branch main
  - nothing to commit, working tree clean