# AWS IAM – Real-Time Hands-On Labs Repository:

Welcome to the **AWS IAM (Identity & Access Management) Hands-On Labs** repository.  
This project provides **practical, real-world IAM scenarios** used every day by Cloud, DevOps, and Security Engineers.

Each lab simulates real-world tasks performed in enterprise AWS environments—such as granting controlled access, restricting actions, enabling cross-account permissions, enforcing MFA, and implementing least-privilege policies.

---

## What is AWS IAM?

AWS Identity and Access Management (IAM) allows you to:

- Control access to AWS resources  
- Manage users, groups, roles, and policies  
- Enforce least-privilege access  
- Apply security governance across AWS accounts  
- Provide temporary credentials via STS  
- Enable cross-account access  
- Implement conditional access (IP-based, MFA-required, time-based)

IAM is global, secure, and essential for every AWS workload.

---

## Purpose of This Repository:

This repository helps you:

✔ Understand IAM through real-world labs  
✔ Practice IAM configuration with guided exercises  
✔ Learn how policies, roles, groups, and permissions interact  
✔ Build job-ready AWS security skills  
✔ Prepare for AWS certifications (SAA, SysOps, SAP, Security Specialty)

---

## Repository Structure:

```
aws-iam-labs/
│
├── README.md                          # Main documentation (this file)
│
├── iam-labs/                               # All IAM-focused hands-on labs
│   ├── README.md                      # IAM overview + lab descriptions
│   ├── lab1-s3-single-bucket-access/
│   ├── lab2-temporary-access/
│   ├── lab3-group-based-access/
│   ├── lab4-ec2-start-stop-access/
│   ├── lab5-s3-delete-restriction/
│   ├── lab6-mfa-enforcement/
│   ├── lab7-ec2-s3-access-role/
│   ├── lab8-lambda-secrets-access/
│   ├── lab9-cross-account-s3-access/
│   ├── lab10-ip-restriction/
│   ├── lab11-time-restriction/
│   ├── lab12-scp-region-restriction/
│   ├── lab13-lambda-dynamodb-access/
│   ├── lab14-prevent-iam-deletion/
│   ├── lab15-abac-ec2-tag-based/
```

---

## List of Hands-On IAM Labs

| Lab No. | Lab Title | Key Concepts |
|--------|-----------|--------------|
| **Lab 1** | Give Developer Access Only to One S3 Bucket | Resource-level IAM, least privilege |
| **Lab 2** | Temporary Access for External Auditor | STS AssumeRole, temporary credentials |
| **Lab 3** | Same Access for New Developer via Groups | IAM groups, permission inheritance |
| **Lab 4** | Allow Start/Stop EC2 Only | Custom IAM policies, Deny rules |
| **Lab 5** | Restrict Delete Access to Security Team | S3 bucket policy, explicit deny |
| **Lab 6** | Enforce MFA for All IAM Users | IAM conditions, MFA enforcement |
| **Lab 7** | Allow EC2 to Read S3 via Role | Instance roles, metadata credentials |
| **Lab 8** | Lambda Access to RDS Credentials | Secrets Manager, Lambda execution role |
| **Lab 9** | Cross-Account S3 Access | Trust policies, role assumption |
| **Lab 10** | Restrict AWS Console Access by IP | Conditional access, security controls |
| **Lab 11** | Time-Based Access Restriction | IAM date/time conditions |
| **Lab 12** | SCP to Restrict Region Usage | AWS Organizations, governance |
| **Lab 13** | Lambda Access to Only One DynamoDB Table | Fine-grained permissions |
| **Lab 14** | Prevent IAM User Deletion | Governance locks, explicit deny |
| **Lab 15** | Tag-Based Access Control for EC2 (ABAC) | Attribute-based access control |

---

## Who This Repository Is For?

- Cloud / DevOps / SRE engineers  
- AWS Security Engineers  
- Students preparing for AWS Certifications  
- Developers learning AWS IAM  
- Anyone wanting job-ready IAM skills  

---

## Learning Outcomes:

You will learn:

✔ How IAM policies are evaluated (Allow vs Deny)  
✔ How to design least-privilege access  
✔ How to use IAM roles instead of access keys  
✔ How to secure EC2, S3, Lambda, DynamoDB  
✔ How to configure cross-account permissions  
✔ How to enforce governance using SCPs  
✔ How to troubleshoot IAM “Access Denied” issues  

---

## Getting Started:

1. Navigate to the `iam-labs/` folder  
2. Start with **Lab 1**  
3. Continue each lab in sequence  
4. Apply the concepts in your AWS account  
5. Use this repo as a reference for interviews or projects  

---

## Contributions:

Contributions are welcome!  
Feel free to add additional IAM labs, Terraform modules, diagrams, or improvements.

---

## License:

This project is open-source.  
You may use or modify the content under the repository’s license.

---

## Happy Learning!

Mastering IAM is a critical skill for becoming a strong Cloud or DevOps engineer.
