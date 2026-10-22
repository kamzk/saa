SAA-C03 Topic Guides — Study Index

38 exam-focused topic guides for the AWS Solutions Architect Associate (SAA-C03) exam. Each file follows the same teaching pattern:

The idea — the service explained from zero with a real-world analogy.
Core concepts — exam-tested facts, numbers, tables, and explicit "THE trap" callouts.
Question patterns — realistic exam scenarios with answers and signal keywords.
Pocket card — a keyword → answer table for rapid review.

The goal is to understand why an architectural solution fits the requirements, not simply memorize service definitions.

<button id="pwa-install-button" class="md-button md-button--primary" type="button" onclick="installPWA()" style="display: none;">📲 Install AWS SAAC03</button>

📖 Suggested Reading Order
🏗️ Priority 1: Core Infrastructure

Goal: Master networking, storage, compute, and identity fundamentals first.

??? note "Networking and Content Delivery"
    - [VPC](06-VPC.md) — subnets, NAT, security groups vs NACLs, endpoints, peering, Transit Gateway, PrivateLink.
    - [Route 53](07-Route53.md) — routing policies, health checks, Alias vs CNAME.
    - [CloudFront & Global Accelerator](08-CloudFront-GlobalAccelerator.md) — CDN vs global network acceleration.
    - [Direct Connect & VPN](32-DirectConnect-VPN.md) — hybrid connectivity and encrypted tunnels.
    - [Transit Gateway](33-Transit-Gateway.md) — hub-and-spoke networking.
    - [DNS, IPv6 & Edge Infrastructure](37I-DNS, IPv6 & Edge Infrastructure.md) — DNS, IPv6, and edge concepts.


??? note "Compute"
    - [EC2](03-EC2.md) — instance families, pricing models, placement groups.
    - [ELB & Auto Scaling](05-ELB-AutoScaling.md) — load balancers, health checks, scaling policies.
    - [Lambda](13-Lambda.md) — execution limits, concurrency, VPC access.
    - [ECS & Fargate](14-ECS-Fargate.md) — containers, task definitions, task roles.
    - [EKS & Kubernetes](14B-EKS-Kubernetes.md) — managed Kubernetes and cluster architecture.
    - [Elastic Beanstalk](15-Elastic-Beanstalk.md) — managed deployments and deployment policies.


??? note "Storage"
    - [S3](02-S3.md) — storage classes, encryption, lifecycle, replication, Object Lock.
    - [EBS, EFS & Instance Store](04-EBS-EFS-InstanceStore.md) — block vs file storage and ephemeral disks.
    - [Storage Gateway, DataSync & Transfer Family](25-StorageGateway-DataSync-TransferFamily.md) — hybrid storage and file transfers.
    - [FSx](26-FSx.md) — Windows, Lustre, ONTAP, OpenZFS.
    - [Snow Family](27-Snow-Family.md) — offline data transfer and edge computing.


??? note "Identity and Access Management"
    - [IAM](01-IAM.md) — roles, policies, permissions, STS, cross-account access.

🗄️ Priority 2: Databases

Goal: Learn to choose the right database and understand availability, performance, and scaling trade-offs.

??? note "Database Services"
    - [RDS & Aurora](09-RDS-Aurora.md) — Multi-AZ vs Read Replicas, failover, Aurora scaling.
    - [DynamoDB](10-DynamoDB.md) — DAX, Global Tables, Streams, GSI vs LSI.
    - [ElastiCache](11-ElastiCache.md) — Redis vs Memcached and caching strategies.
    - [Other Databases](12-Other-Databases.md) — specialized database services and database selection.

⚡ Priority 3: Serverless and Application Integration

Goal: Understand decoupling, event-driven architectures, APIs, and workflows.

??? note "Application Services"
    - [API Gateway](16-API-Gateway.md) — authorization, throttling, integrations, timeouts.
    - [SQS, SNS & Kinesis](17-SQS-SNS-Kinesis.md) — queues, fan-out, streaming, decoupling.
    - [EventBridge & Step Functions](18-EventBridge-StepFunctions.md) — event routing and workflows.
    - [Application Development & Integration](37G-Application Development & Integration.md) — additional application and integration services.

🔐 Priority 4: Security and Identity

Goal: Recognize the right security control for encryption, secrets, application identities, and threat protection.

??? note "Security Services"
    - [KMS & CloudHSM](20-KMS-CloudHSM.md) — encryption keys and hardware security modules.
    - [Secrets Manager & Parameter Store](21-SecretsManager-ParameterStore.md) — secret storage, rotation, configuration.
    - [WAF, Shield & Security Services](22-WAF-Shield-SecurityServices.md) — web protection, DDoS mitigation, threat detection.
    - [Cognito](23-Cognito.md) — User Pools vs Identity Pools.
    - [Directory Services](24-Directory-Services.md) — Managed Microsoft AD, AD Connector, Simple AD.
    - [Certificates](37B-Certificates.md) — certificates, TLS, and HTTPS.

📊 Priority 5: Monitoring, Management and Governance

Goal: Understand operational visibility, account governance, infrastructure automation, and cost optimization.

??? note "Monitoring and Operations"
    - [CloudWatch, CloudTrail & Config](19-CloudWatch-CloudTrail-Config.md) — metrics, logs, API auditing, configuration history.
    - [Systems Manager & Operations](37F-Systems Manager & Operations.md) — fleet management, automation, operational visibility.


??? note "Infrastructure and Governance"
    - [CloudFormation](28-CloudFormation.md) — Infrastructure as Code and stacks.
    - [Organizations & Control Tower](29-Organizations-ControlTower.md) — SCPs, multi-account governance, landing zones.
    - [Service Catalog & Trusted Advisor](30-ServiceCatalog-TrustedAdvisor.md) — standardized provisioning and recommendations.
    - [Well-Architected Framework](34-Well-Architected.md) — architectural trade-offs and the six pillars.
    - [Specialized Services & Governance](37H-Specialized Services & Governance.md) — additional governance and specialized services.


??? note "Cost Management"
    - [Cost Management](31-Cost-Management.md) — Cost Explorer, Budgets, Cost and Usage Reports.

📈 Priority 6: Analytics, AI and Data Integration

Goal: Recognize additional AWS services and match them to the requirements in scenario questions.

??? note "Analytics and Data"
    - [Data Lakes, ETL & Data Integration](37C-Data Lakes, ETL & Data Integration.md) — data lakes, ETL, data movement.
    - [Analytics, Big Data & Streaming](37D-Analytics, Big Data & Streaming.md) — analytics, big data, stream processing.
    - [AI & Machine Learning One-Liners](37E-AI & Machine Learning One-Liners.md) — AI/ML service recognition and use cases.

📦 Priority 7: Migration and Disaster Recovery

Goal: Choose the right migration approach and recovery strategy based on RPO, RTO, cost, and operational requirements.

??? note "Migration and Resilience"
    - [Disaster Recovery](35-Disaster-Recovery.md) — RPO/RTO, backup and restore, pilot light, warm standby, multi-site.
    - [Migration, Messaging & Disaster Recovery](37A-Migration, Messaging & Disaster Recovery.md) — migration options, messaging patterns, recovery scenarios.

🎯 Priority 8: Final Review

Goal: Consolidate your knowledge, eliminate distractors, and revisit common exam traps.

??? note "Exam Preparation"
    - [Exam Traps & Key Patterns](36-Exam-Traps-KeyPatterns.md) — common traps, service comparisons, scenario keywords.
    - [Elimination Rules](38-elimination rules.md) — eliminating distractors and selecting answers against requirements.

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
