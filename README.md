# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS

## NAME: VISWAPRIYA S
## REG.NO: 212225230311
## Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
## Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
## Procedure
## a)	Steps to Create a first S3 Bucket:
## Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
## Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
## Step 3: Create Bucket
Click the Create bucket button.
## Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
## Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
## Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
## Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
## Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
## Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
## Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
## b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

## c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

## d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.

Snap Shot 1: Simple Storage Service (S3):

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9f07bcf3-46c4-4821-9434-f4573157fd9b" />

 

Snap Shot 2:  EC2 (Elastic Compute Cloud) – Instance

<img width="1920" height="1080" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/ed313885-8838-4c1c-a48a-7aa5bd169799" />

<img width="1920" height="1080" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/cd00cfef-5f49-414f-b68c-b618bb6e214c" />

<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/fffe31a1-0199-4fa9-b6ac-3865c4de6423" />

<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/5e350ae7-14cc-49c0-82d3-275a9d097d9a" />

<img width="1920" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/fcd5659a-72d1-4807-9358-b02485155161" />

<img width="1920" height="1080" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/2b103db1-9c02-40aa-b80d-13ee117d5800" />

<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/778bda1d-52dc-401e-a633-03daa8cf0856" />

<img width="1920" height="1080" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/a72a62cf-a11c-436e-9663-d78d72b62d83" />

<img width="1920" height="1080" alt="Screenshot (59)" src="https://github.com/user-attachments/assets/fd2d49e3-8ac6-42b5-948d-43bf22f1935b" />

<img width="1920" height="1080" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/e2bd560a-1be3-4c86-b614-976f4d3a90a4" />

<img width="1920" height="1080" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/0c7917dd-568d-4b88-af2b-ccbd498f1db2" />

<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/0fcef1e5-8c42-40e5-adc9-e9b3c9a3041a" />

<img width="1920" height="1080" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/8931463e-5cd6-455f-a262-57d4dfd02b5f" />

<img width="1920" height="1080" alt="Screenshot (66)" src="https://github.com/user-attachments/assets/33c8fe4b-d1fc-45c4-a73e-827a07e34504" />














## Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
