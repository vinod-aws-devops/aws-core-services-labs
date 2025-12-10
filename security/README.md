
---

## Skills Demonstrated:

These security labs highlight essential AWS competencies:

### Identity & Access Management: 
- IAM users, groups, policies  
- JSON policy writing and debugging  
- IAM roles for EC2, Lambda, and cross-service access  
- Permission boundaries  
- MFA enforcement and credential hardening  

### Encryption & Key Management:
- KMS CMK creation & rotation  
- Envelope encryption  
- Encrypting S3, EBS, RDS, Secrets Manager  

### Secrets & Credentials Management :
- Storing and retrieving credentials securely  
- Automating secret rotation  
- Lambda-to-Secrets Manager access  

### Multi-Account Security: 
- AWS Organizations  
- Service Control Policies (SCPs)  
- Restricting usage of sensitive services  

---

## Architecture Examples Covered:

Some labs include diagrams illustrating:

- IAM evaluation logic (Allow vs Deny)  
- Cross-account access with roles & trust relationships  
- S3 bucket policy cross-account permissions  
- KMS encryption workflow  
- SCP hierarchy and policy enforcement  

---

## How To Use This Folder:

1. Open any lab folder (e.g., `lab1-s3-single-bucket-access/`)  
2. Read the **README.md** inside for step-by-step instructions  
3. View the **architecture-diagram** for understanding  
4. Deploy using Terraform (if provided)  
5. Validate using screenshots or AWS CLI output  

Each lab is isolated, so you can practice them independently.

---

## Real-World Use Cases You Will Learn:

- Restricting developers to specific AWS services  
- Enforcing encryption standards (finance/healthcare use cases)  
- Preventing privilege escalation  
- Managing cross-account roles in enterprise setups  
- Creating scalable and secure IAM architectures  
- Protecting sensitive data with KMS & Secrets Manager  

---

## Prerequisites:

- Basic AWS IAM knowledge  
- AWS CLI configured  
- Optional: Terraform installed  
- Admin or sandbox AWS account  

---

## Roadmap for Additional Security Labs:

- IAM Access Analyzer scenarios  
- CloudTrail + GuardDuty security monitoring  
- KMS multi-region keys + disaster recovery  
- Security Hub + Compliance automation (CIS, PCI-DSS)  

---

## ⭐ Give a Star!

If you find these labs helpful, consider starring the main repository to support further improvements.

