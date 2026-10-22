# AWS Solutions Architect Associate (SAA-C03) — Topic Guides

**38 exam-focused study guides covering the major AWS Solutions Architect Associate (SAA-C03) topics** — explained the way a good teacher explains them, rather than reading like service documentation.

## What makes these different

Every guide follows the same teaching format:

1. **The idea** — each service explained from zero using a real-world analogy.
2. **Core concepts** — exam-relevant facts, limits, defaults, distinctions, and explicit **"THE trap"** callouts highlighting common mistakes.
3. **Question patterns** — realistic exam-style scenarios, with answers and the keywords that help identify the correct solution.
4. **Pocket card** — a keyword → answer table for rapid revision.

The guides emphasize decision patterns that commonly matter in SAA-C03 scenarios, such as:

- Multi-AZ vs. Read Replicas
- Gateway vs. Interface VPC Endpoints
- SQS vs. SNS vs. Kinesis vs. EventBridge
- RDS vs. Aurora vs. DynamoDB
- NAT Gateway vs. VPC Endpoints
- CloudFront vs. Global Accelerator
- Backup and restore vs. pilot light vs. warm standby

The goal is to understand **why a solution fits the requirements**, not simply memorize service definitions.

---

## Start here

📖 **Topic Guides Index** — browse all 38 guides below, organized by study priority and topic.

\<button id="pwa-install-button" class="md-button md-button--primary" type="button" onclick="installPWA()" style="display: none;"\>📲 Install AWS SAA-C03 Notes\</button\>

### High-value guides to prioritize

If you're short on time, consider starting with these topics. This is a practical study recommendation, not an official ranking of individual service question frequency.

- VPC — networking fundamentals, routing, endpoints, connectivity, and security controls.
- S3 — storage classes, encryption, lifecycle policies, replication, and data protection.
- RDS & Aurora — Multi-AZ, Read Replicas, failover, scaling, and database selection.
- SQS, SNS & Kinesis — messaging, event-driven architectures, streaming, and decoupling.
- Exam Traps & Key Patterns — review after studying the underlying services, then revisit during final revision.

---

## Official exam-domain weights

AWS organizes the scored SAA-C03 content into four domains:

| Exam domain | Weight |
| --- | --- |
| Design Secure Architectures | 30% |
| Design Resilient Architectures | 26% |
| Design High-Performing Architectures | 24% |
| Design Cost-Optimized Architectures | 20% |

These percentages describe the official exam domains, not the frequency of individual services or question patterns. Use the weights to guide your overall preparation, but don't neglect a domain or service solely because it seems less prominent.

**Official reference:** [AWS Certified Solutions Architect – Associate (SAA-C03) Exam Guide](<https://docs.aws.amazon.com/aws-certification/latest/solutions-architect-associate-03.html>)

---

# 🚨 Priority 1: Core AWS Services

**Goal:** Build a strong foundation in identity, storage, compute, networking, databases, and security.

??? note "00 — Start Here"

```
- [Topic Guides Index](00-README.md)
```

??? note "01 — Identity and Access Management"

```
- [IAM](01-IAM.md)
```

??? note "02 — Storage"

```
- [Amazon S3](02-S3.md)
- [EBS, EFS & Instance Store](04-EBS-EFS-InstanceStore.md)
- [Storage Gateway, DataSync & Transfer Family](25-StorageGateway-DataSync-TransferFamily.md)
- [Amazon FSx](26-FSx.md)
- [Snow Family](27-Snow-Family.md)
```

??? note "03 — Compute"

```
- [Amazon EC2](03-EC2.md)
- [ELB & Auto Scaling](05-ELB-AutoScaling.md)
- [AWS Lambda](13-Lambda.md)
- [ECS & Fargate](14-ECS-Fargate.md)
- [EKS & Kubernetes](14B-EKS-Kubernetes.md)
- [Elastic Beanstalk](15-Elastic-Beanstalk.md)
```

??? note "04 — Networking and Content Delivery"

```
- [Amazon VPC](06-VPC.md)
- [Amazon Route 53](07-Route53.md)
- [CloudFront & Global Accelerator](08-CloudFront-GlobalAccelerator.md)
- [Direct Connect & VPN](32-DirectConnect-VPN.md)
- [Transit Gateway](33-Transit-Gateway.md)
- [DNS, IPv6 & Edge Infrastructure](37I-DNS, IPv6 & Edge Infrastructure.md)
```

??? note "05 — Databases"

```
- [RDS & Aurora](09-RDS-Aurora.md)
- [Amazon DynamoDB](10-DynamoDB.md)
- [Amazon ElastiCache](11-ElastiCache.md)
- [Other Databases](12-Other-Databases.md)
```

??? note "06 — Messaging and Application Integration"

```
- [API Gateway](16-API-Gateway.md)
- [SQS, SNS & Kinesis](17-SQS-SNS-Kinesis.md)
- [EventBridge & Step Functions](18-EventBridge-StepFunctions.md)
- [Application Development & Integration](37G-Application Development & Integration.md)
```

??? note "07 — Security and Protection"

```
- [KMS & CloudHSM](20-KMS-CloudHSM.md)
- [Secrets Manager & Parameter Store](21-SecretsManager-ParameterStore.md)
- [WAF, Shield & Security Services](22-WAF-Shield-SecurityServices.md)
- [Amazon Cognito](23-Cognito.md)
- [Directory Services](24-Directory-Services.md)
- [Certificates](37B-Certificates.md)
```

---

# 🏗️ Priority 2: Architecture and Resilience

**Goal:** Understand how to design highly available, fault-tolerant, scalable, and loosely coupled systems.

??? note "08 — High Availability and Disaster Recovery"

```
- [Disaster Recovery](35-Disaster-Recovery.md)
- [Migration, Messaging & Disaster Recovery](37A-Migration, Messaging & Disaster Recovery.md)
```

??? note "09 — Infrastructure as Code"

```
- [AWS CloudFormation](28-CloudFormation.md)
```

??? note "10 — Well-Architected Design"

```
- [AWS Well-Architected Framework](34-Well-Architected.md)
```

??? note "11 — Exam Traps and Architecture Patterns"

```
- [Exam Traps & Key Patterns](36-Exam-Traps-KeyPatterns.md)
- [Elimination Rules](38-elimination rules.md)
```

---

# ⚙️ Priority 3: Operations, Governance and Cost

**Goal:** Learn how to monitor, manage, govern, and optimize AWS environments.

??? note "12 — Monitoring and Auditing"

```
- [CloudWatch, CloudTrail & Config](19-CloudWatch-CloudTrail-Config.md)
- [Systems Manager & Operations](37F-Systems Manager & Operations.md)
```

??? note "13 — Governance and Multi-Account Management"

```
- [Organizations & Control Tower](29-Organizations-ControlTower.md)
- [Service Catalog & Trusted Advisor](30-ServiceCatalog-TrustedAdvisor.md)
- [Specialized Services & Governance](37H-Specialized Services & Governance.md)
```

??? note "14 — Cost Optimization"

```
- [Cost Management](31-Cost-Management.md)
```

---

# 🔍 Priority 4: Additional Services and Knowledge Gaps

**Goal:** Recognize less frequently emphasized services and identify the right solution when they appear in a scenario.

??? note "15 — Data Lakes, ETL and Data Integration"

```
- [Data Lakes, ETL & Data Integration](37C-Data Lakes, ETL & Data Integration.md)
```

??? note "16 — Analytics, Big Data and Streaming"

```
- [Analytics, Big Data & Streaming](37D-Analytics, Big Data & Streaming.md)
```

??? note "17 — AI and Machine Learning"

```
- [AI & Machine Learning One-Liners](37E-AI & Machine Learning One-Liners.md)
```

---

# 🧠 Exam-Technique Rules

## 1\. Identify the actual requirement

You can start by reading the final sentence to identify what the question asks for. Then read the entire scenario carefully.

Distinguish between requirements such as:

- **MOST cost-effective**
- **LEAST operational overhead**
- **HIGHLY available**
- **MINIMUM latency**
- **NEAR-ZERO data loss**
- **MINIMUM recovery time**

The best solution depends on the complete set of requirements, not just the service named in the question.

## 2\. Count every requirement

Treat phrases such as "X as well as Y" as a checklist. The correct answer must satisfy every required condition.

If a question asks for both private connectivity and high availability, an option that provides only private connectivity is incomplete.

## 3\. Pay attention to qualifying words

Words and phrases such as **serverless, automatically, at no additional cost, immediately, directly, cannot, and always** can change whether an answer is correct.

Don't reject an answer simply because it uses an absolute term. Check whether the statement is actually true for the specified service, configuration, and situation.

## 4\. Compare similar answer choices carefully

When two options appear almost identical, examine their differences:

- Which one satisfies all requirements?
- Which one introduces an unnecessary component?
- Which one requires more operational work?
- Which one fails a stated performance, availability, security, or cost constraint?

A single qualification can determine the correct answer.

## 5\. Use numerical requirements to eliminate options

Pay attention to stated limits and targets, including:

- Retrieval time and storage durability
- IOPS and throughput
- Recovery Point Objective (RPO) and Recovery Time Objective (RTO)
- Timeout limits
- Data-transfer volume
- Capacity and scaling requirements

Use the values to eliminate incompatible solutions before comparing the remaining options.

Verify unfamiliar or potentially outdated numbers against current AWS documentation.

## 6\. Don't guess based on how familiar an option sounds

An unfamiliar service feature can be correct, but unfamiliarity alone doesn't make an option more likely to be right.

If none of the familiar choices appears suitable:

1. Re-read the exact requirement.
2. Identify which requirement eliminates each plausible option.
3. Check whether an unfamiliar service or feature fits the scenario.
4. Verify its actual behavior and limitations if necessary.

Choose the answer that satisfies the requirements, not the one that sounds most sophisticated or most familiar.

## 7\. Prefer the simplest solution that meets every requirement

When several options work, consider operational overhead, cost, availability, scalability, and security.

Don't automatically select the cheapest service if it fails a reliability or performance requirement. Likewise, don't select a more complex architecture when a managed service meets all the stated requirements.

---

# 📚 Accuracy and Disclaimer

These are community study notes, not official AWS exam content. They are not affiliated with or endorsed by Amazon Web Services.

The guides are intended to explain concepts and help you practice architectural decisions. They should not be treated as a guarantee of complete exam coverage or as a substitute for the official exam guide.

AWS service features, quotas, pricing, regional availability, and product lifecycles can change. Before relying on a specific limit or behavior:

- Check the current official AWS documentation.
- Verify that the service and feature remain supported.
- Distinguish default settings from maximum configurable limits.
- Pay attention to exceptions and prerequisites.
- Use the current SAA-C03 exam guide to confirm the scope of your preparation.

**Official exam guide:** [AWS Certified Solutions Architect – Associate (SAA-C03)](<https://docs.aws.amazon.com/aws-certification/latest/solutions-architect-associate-03.html>)