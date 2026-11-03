# NAME : POPURI ADITYA NAGA SAI
# REG NO : 212223110036

# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


Snap Shots:
<img width="1920" height="1080" alt="Screenshot 2026-11-03 112341" src="https://github.com/user-attachments/assets/3c2e1f74-32b7-48cb-8119-4c52e24e3784" />
<img width="1920" height="1080" alt="Screenshot 2026-11-03 112614" src="https://github.com/user-attachments/assets/fca06ab8-3880-473c-b1cb-b89ea2abc7c9" />
<img width="1920" height="1080" alt="Screenshot 2026-11-03 112625" src="https://github.com/user-attachments/assets/65388232-4d2f-484a-91e5-69025385cc17" />
<img width="1920" height="1080" alt="Screenshot 2026-11-03 112840" src="https://github.com/user-attachments/assets/c112a589-aa63-4003-8a7e-46b7a5843d98" />
<img width="1920" height="1080" alt="Screenshot 2026-11-03 113510" src="https://github.com/user-attachments/assets/cd4f77e9-d16a-4043-ac23-7565ba84b05a" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f75a8ff7-7302-4380-9399-5b96e209f9f5" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/334aa86e-cbc0-4093-a37f-1e3c69c987e3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5de7af8a-51ac-4d04-8b7a-333bf8ae1ddc" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cac6bf1d-90a7-410f-815d-d659187b865c" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/039d224a-1a5c-4d57-8b45-918d208ee6d3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e3f52fd9-920c-45fb-8186-9cee0852e4fc" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cc491302-bd1d-4754-b237-05d03033c364" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b952dbe1-cd02-4b7a-8584-e23a04c28312" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f0e7af0d-00fb-414f-84a1-abfab086a824" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/26778859-1729-4f5a-af9d-9a61faacdad6" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fb2e0469-7515-42a4-bc53-e4190c2ca773" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0b0f0313-cde5-490e-a2df-7f6ede29a08f" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/126562c1-e627-4ddc-8fc2-45e7f3dbad01" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/abfd7ff6-f011-4138-85c4-2ffa3ba1c0eb" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ac7eb36e-c3a8-44d6-a4df-6189ffaab292" />


























Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
