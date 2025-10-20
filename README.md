# Task-1-elevate-labs

🎯 Objective
Understand the basics of cloud object storage and learn how to create and manage storage buckets effectively using AWS S3.

☁️ What Are Buckets in AWS S3?

In Amazon S3 (Simple Storage Service), a bucket is like a container that holds your data such as text files, images, videos, and backups.
Each bucket has a globally unique name and is used to organize and store objects (files) in the cloud.

Buckets help you:

Store and access files securely from anywhere.

Manage permissions for public or private access.

Control data location using regions for better performance and compliance.

Integrate with other AWS services for automation or analysis.

🧰 Tools Used

Amazon Web Services (AWS) – S3 (Free Tier)

AWS Management Console

🚀 Steps to Create and Use an S3 Bucket

1. Sign In or Create an AWS Account

Go to AWS Free Tier and sign in with your account.

2. Create a New Bucket

Navigate to S3 → Buckets → Create bucket.
Enter a unique bucket name (e.g., my-first-s3-bucket-demo).
Choose a region close to you (for example, us-east-1).
Keep the default settings unless you have specific security or versioning needs.
Click Create bucket.

3. Upload a File

Open your new bucket → Click Upload → Select a small file (e.g., hello.txt or an image).
Wait for the upload to complete successfully.

4. Set Permissions (Optional)

If you want to make the file publicly accessible:
Select the file → Click Actions → Make public using ACL (if enabled).
Copy the Object URL that appears after making it public.

5. Test and Verify

Paste the copied Object URL into your browser.
If permissions are correct, your file will open successfully.
Take a screenshot showing your uploaded file in the S3 console.
