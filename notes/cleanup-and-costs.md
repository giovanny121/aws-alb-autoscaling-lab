# Cleanup & Costs
- Set ASG Desired=0 → delete ASG and Launch Template
- Delete Target Group and ALB
- Remove unused security groups
- Note: RDS Multi-AZ and EKS are not Free Tier; this project used ALB + EC2 + ASG only.

