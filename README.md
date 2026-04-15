# AWS-IAM-Configuration-Lab

## Project Overview
This lab involved configuring identity and access management security standards within an AWS environment. The focus was on implementing the **Principle of Least Privilege (PoLP)** to ensure users had only the access necessary for their specific job functions.

## Key Objectives
* **Security Baselines:** Established a custom account-wide password policy (10+ characters, multi-factor requirements).
* **Access Control:** Managed three distinct user groups with specific managed and inline policies:
    * `S3-Support`: Read-only access to Amazon S3.
    * `EC2-Support`: Read-only access to Amazon EC2.
    * `EC2-Admin`: Administrative rights to view, start, and stop EC2 instances.
* **Validation:** Conducted cross-user testing using the IAM sign-in URL to verify permission boundaries and unauthorized access blocks.

## Technical Skills Applied
* AWS IAM (Users, Groups, Policies)
* JSON Policy Inspection
* Cloud Security Best Practices
* Access Troubleshooting
