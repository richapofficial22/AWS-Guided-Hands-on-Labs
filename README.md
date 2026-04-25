# AWS Guided Hands-on Labs 
Guided labs completed during AWS Certified Cloud Practitioner preparation (AWS Skill
Builder, 33-hour course). These are structured lab exercises — not independent projects.
Each lab used real AWS services in the AWS Management Console under guided objectives.
##
## Lab 1 :
- Objective: 
  - Demonstrate how to create an S3 bucket and upload an object to it.
  - Demonstrate how to add a bucket policy to secure access to the bucket and the object in it.
- Amazon services used :
  - Amazon Simple Storage Service
- Key Takeaways:
  - Difference between public access block settings, bucket policies, and
object-level ACLs. How bucket policies use JSON condition keys to restrict access by IP or
IAM principal.
  - Understanding this distinction matters in
production because misconfigured S3 permissions are one of the most common causes of AWS data
exposure incidents — the bucket policy is the gatekeeper, not the object's own settings.
- Evidence of completion:
  - <img width="1428" height="797" alt="Screenshot 2026-03-14 at 12 56 27 PM" src="https://github.com/user-attachments/assets/9f4f902c-ff0b-4742-b956-66958649aaeb" />
  - <img width="840" height="632" alt="Screenshot 2026-03-16 at 8 22 07 PM" src="https://github.com/user-attachments/assets/be2ff89d-fa09-4d4e-8d2c-27bbcaba983e" />
##
## Lab 2 :
- Objective:
  - Demonstrate how to invoke an AWS Lambda function to log the state of an Amazon EC2 instance.
  - Demonstrate how to create an Amazon EventBridge rule to monitor the state of the EC2 instance by using a Lambda function.
- Amazon services used :
  - Amazon CloudWatch, Amazon Elastic Compute Cloud, Amazon EventBridge, AWS Lambda
- Key Takeaways:
  - Event-driven architecture pattern — EventBridge routes EC2 lifecycle events
to Lambda without polling. Lambda logs results to CloudWatch. This is how production teams
monitor infrastructure state changes without dedicated monitoring servers.
- Evidence of completion:
  - <img width="1440" height="900" alt="Screenshot 2026-03-14 at 6 56 37 PM" src="https://github.com/user-attachments/assets/331f897c-632e-47b2-9908-f151356ab6e3" />
  - <img width="842" height="614" alt="Screenshot 2026-03-16 at 9 28 27 PM" src="https://github.com/user-attachments/assets/405573cd-ace7-4421-bac1-4e6a659550bf" />
##
## Lab 3 :
- Objective:
  - Determine how to create an Amazon EC2 instance and an Amazon EBS volume.
  - Determine how to create an AMI from the instance.
  - Determine how to terminate the EC2 instance and delete the EBS volume.
- Amazon services used:
  - Amazon Elastic Compute Cloud
- Key Takeaways:
  - Relationship between EC2 and EBS (compute vs persistent storage). AMI as a
point-in-time snapshot used for backup or to launch identical instances.
  - Importance of cleanup to avoid ongoing AWS charges.
- Evidence of completion :
  - <img width="1440" height="900" alt="Screenshot 2026-03-19 at 6 16 57 PM" src="https://github.com/user-attachments/assets/d04ed582-2b56-4464-b203-a78b441fafe4" />
  - <img width="841" height="654" alt="Screenshot 2026-03-19 at 6 23 22 PM" src="https://github.com/user-attachments/assets/22a99e29-29f7-4c34-8e0d-c4c7dc94d8a2" />

##
**What comes next:** These guided labs gave me hands-on console experience 
across 7 AWS services and the foundation to start building independently. 
I am currently building independent projects — each one designed from scratch, 
with architecture decisions, documentation, and deployment done entirely by me. 
As projects go live, I will link them here.
##
  - Part of AWS CCP preparation | AWS Certified Cloud Practitioner achieved April 3, 2026
  - Credential ID: 4c140c1e9cae439b89b1f35a03d48ac1
##
