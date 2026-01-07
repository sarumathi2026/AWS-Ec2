# AWS-Ec2
Real-world AWS EC2 project with IAM, EBS, AMI, and security best practices
# Secure EC2 Infrastructure on AWS

## Business Problem
A company needs a secure AWS infrastructure to host internal applications with controlled access, data encryption, and backup.
## AWS Services Used
- IAM
- EC2
- EBS
- AMI
- EFS
- Elastic IP
## What I Implemented
- Secured root account using MFA
- Created IAM users with least privilege access
- Launched EC2 instances
- Used public and private IPs
- Configured SSH access
- Attached and encrypted EBS volumes
- Created EBS snapshots for backup
- Created AMI for disaster recovery
- Mounted EFS to EC2 instances
## Security Best Practices
- MFA enabled
- No direct access to root account
- Restricted SSH using security groups
- Encrypted storage
## Cost Optimization
- Used On-Demand instances
- Understood Spot and Reserved instances
## Backup & Recovery
- Used EBS snapshots
- Created AMI for quick recovery
