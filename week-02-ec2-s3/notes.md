Week 2 – EC2 & S3 Hands-On

Setup
 Since my AWS account's payment verification failed (blocking live EC2/S3 access), I used Docker + LocalStack, a free local AWS emulator, to get real hands-on practice with AWS CLI commands.

What I Did

Installed Docker and ran a LocalStack container
Configured AWS CLI to point to LocalStack
Created my first S3 bucket
Created my first IAM user (test-user)
Attached a read-only S3 policy to test-user (least privilege practice)

What I Learned

S3 is object storage. One of the biggest real-world security risks is accidentally leaving buckets public.
IAM users are separate identities with their own permissions. Never use the root or admin account for daily work.
Least privilege means giving users only the access they need. I gave test-user read-only S3 access instead of full access, so if credentials were compromised, potential damage would be limited.
EC2 is a virtual server (compute), while S3 is storage. Launching an EC2 instance requires an AMI (OS template), instance type, key pair, and security group.
Provide your feedback on BizChat
