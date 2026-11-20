SAA-C03 Topic Guides — Study Index

38 exam-focused topic guides for the AWS Solutions Architect Associate (SAA-C03) exam. Each file follows the same teaching pattern:

The idea — the service explained from zero with a real-world analogy.
Core concepts — exam-tested facts, numbers, tables, and explicit "THE trap" callouts.
Question patterns — realistic exam scenarios with answers and signal keywords.
Pocket card — a keyword → answer table for rapid review.

The goal is to understand why an architectural solution fits the requirements, not simply memorize service definitions.

<button id="pwa-install-button" class="md-button md-button--primary" type="button" onclick="installPWA()" style="display: none;">📲 Install AWS SAAC3</button>

📖 Suggested Reading Order

🏗️ Priority 1: Core Infrastructure

??? note "Networking and Content Delivery"
    - [VPC](06-VPC.md)
    - [Route 53](07-Route53.md)
    - [CloudFront & Global Accelerator](08-CloudFront-GlobalAccelerator.md)
    - [Direct Connect & VPN](32-DirectConnect-VPN.md)
    - [Transit Gateway](33-Transit-Gateway.md)
    - [DNS, IPv6 & Edge Infrastructure](37I-DNS, IPv6 & Edge Infrastructure.md)

??? note "Compute"
    - [EC2](03-EC2.md)
    - [ELB & Auto Scaling](05-ELB-AutoScaling.md)
    - [Lambda](13-Lambda.md)
    - [ECS & Fargate](14-ECS-Fargate.md)
    - [EKS & Kubernetes](14B-EKS-Kubernetes.md)
    - [Elastic Beanstalk](15-Elastic-Beanstalk.md)

??? note "Storage"
    - [S3](02-S3.md) — storage classes, encryption, lifecycle, replication, Object Lock.
    - [EBS, EFS & Instance Store](04-EBS-EFS-InstanceStore.md) — block vs file storage and ephemeral disks.
    - [Storage Gateway, DataSync & Transfer Family](25-StorageGateway-DataSync-TransferFamily.md) — hybrid storage and file transfers.
    - [FSx](26-FSx.md) — Windows, Lustre, ONTAP, OpenZFS.
    - [Snow Family](27-Snow-Family.md) — offline data transfer and edge computing.

??? note "Identity and Access Management"
    - [IAM](01-IAM.md) — roles, policies, permissions, STS, cross-account access.

🗄️ Priority 2: Databases

??? note "Database Services"
    - [RDS & Aurora](09-RDS-Aurora.md)
    - [DynamoDB](10-DynamoDB.md)
    - [ElastiCache](11-ElastiCache.md)
    - [Other Databases](12-Other-Databases.md)

⚡ Priority 3: Serverless and Application Integration

??? note "Application Services"
    - [API Gateway](16-API-Gateway.md)
    - [SQS, SNS & Kinesis](17-SQS-SNS-Kinesis.md)
    - [EventBridge & Step Functions](18-EventBridge-StepFunctions.md)
    - [Application Development & Integration](37G-Application Development & Integration.md)

🔐 Priority 4: Security and Identity

??? note "Security Services"
    - [KMS & CloudHSM](20-KMS-CloudHSM.md)
    - [Secrets Manager & Parameter Store](21-SecretsManager-ParameterStore.md)
    - [WAF, Shield & Security Services](22-WAF-Shield-SecurityServices.md)
    - [Cognito](23-Cognito.md)
    - [Directory Services](24-Directory-Services.md)
    - [Certificates](37B-Certificates.md)

📊 Priority 5: Monitoring, Management and Governance

??? note "Monitoring and Operations"
    - [CloudWatch, CloudTrail & Config](19-CloudWatch-CloudTrail-Config.md)
    - [Systems Manager & Operations](37F-Systems Manager & Operations.md)


??? note "Infrastructure and Governance"
    - [CloudFormation](28-CloudFormation.md)
    - [Organizations & Control Tower](29-Organizations-ControlTower.md)
    - [Service Catalog & Trusted Advisor](30-ServiceCatalog-TrustedAdvisor.md)
    - [Well-Architected Framework](34-Well-Architected.md)
    - [Specialized Services & Governance](37H-Specialized Services & Governance.md)


??? note "Cost Management"
    - [Cost Management](31-Cost-Management.md)

📈 Priority 6: Analytics, AI and Data Integration

??? note "Analytics and Data"
    - [Data Lakes, ETL & Data Integration](37C-Data Lakes, ETL & Data Integration.md)
    - [Analytics, Big Data & Streaming](37D-Analytics, Big Data & Streaming.md)
    - [AI & Machine Learning One-Liners](37E-AI & Machine Learning One-Liners.md)

📦 Priority 7: Migration and Disaster Recovery

??? note "Migration and Resilience"
    - [Disaster Recovery](35-Disaster-Recovery.md)
    - [Migration, Messaging & Disaster Recovery](37A-Migration, Messaging & Disaster Recovery.md)

🎯 Priority 8: Final Review

??? note "Exam Preparation"
    - [Exam Traps & Key Patterns](36-Exam-Traps-KeyPatterns.md)
    - [Elimination Rules](38-elimination rules.md)

🧠 How to Use These Guides
First pass: Follow the suggested reading order. Focus on the analogies and understand what each service solves.
Second pass: Cover the answer columns in the pocket cards and quiz yourself using the keywords.
After practice tests: For every incorrect answer, revisit that topic's Question Patterns section. Identify the signal words or constraints you missed.
Exam morning: Review guides 36 and 38, then skim the pocket cards. Reinforce what you know rather than trying to learn everything from scratch.
📊 Official Exam-Domain Weights
Exam domain	Weight
Design Secure Architectures	30%
Design Resilient Architectures	26%
Design High-Performing Architectures	24%
Design Cost-Optimized Architectures	20%

These weights apply to the official exam domains, not individual AWS services. Use them to balance your preparation rather than predict the frequency of specific service questions.
