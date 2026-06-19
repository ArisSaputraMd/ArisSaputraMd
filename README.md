## Hi, I'm Muhammad Aris

Cloud Engineer in transition — AWS SAA-C03 · CompTIA Network+ · CompTIA Security+

I build production-like infrastructure on AWS using Terraform and document the decisions, trade-offs, and failures that actually happened. No tutorials reproduced, no hello-world containers — complete systems built end-to-end and torn down cleanly.

Currently based in Indonesia. Open to cloud engineering, cloud support, and junior DevOps roles — on-site or remote.

---

What I'm building

aws-secure-infrastructure — a production-grade Mattermost deployment on ECS Fargate, built with Terraform and designed around zero NAT Gateway dependency, SSM-based secrets management, and least-privilege IAM across every role boundary.

The stack: Route 53 → ACM → ALB → ECS Fargate → RDS PostgreSQL, all in private subnets with VPC Interface Endpoints replacing NAT Gateway for ECR, S3, SSM, and CloudWatch Logs.

Things I diagnosed and fixed during the build: IAM execution role permission chain failure, PostgreSQL DSN URL encoding error, ECS task role propagation mismatch, ACM/DNS validation stall, CloudFront/WebSocket protocol incompatibility. All documented in the repo with root cause and resolution.

---

Skills

| Area | Tools | 
| Cloud | AWS — ECS Fargate, RDS, ALB, ACM, Route 53, SSM Parameter Store, VPC, IAM, CloudWatch | 
| IaC | Terraform (modular, multi-environment parameterized) |
| Containers | Docker, ECS task definitions, ECR |
| Networking | VPC design, private subnets, security groups, DNS, load balancing, TCP/IP | 
| Security | Least-privilege IAM, secrets management via SSM, TLS, network segmentation | 
| DevOps basics | Git, Bash, Linux |

---

Certifications


- AWS Certified Solutions Architect – Associate (SAA-C03) | [Verify](https://cp.certmetrics.com/amazon/en/public/verify/credential/bb0b08a1d2ca47f69819803145d015ff)
- CompTIA Network+ | [Verify](https://cp.certmetrics.com/comptia/en/public/verify/credential/a26e16f4e6c74261b0aa4b2e767d19ce)
- CompTIA Security+ | [Verify](https://cp.certmetrics.com/comptia/en/public/verify/credential/2613a0f604464629aa98c0b66493a498)

---

Contact

linkedin.com/in/aris-saputra-md · arissaputramuhammad7@gmail.com
