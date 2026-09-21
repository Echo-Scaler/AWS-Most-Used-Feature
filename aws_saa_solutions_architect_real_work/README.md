# AWS Certified Solutions Architect - Associate (SAA-C03) & Real-World Cloud Engineering Master Course (မြန်မာဘာသာ အပြည့်အစုံ)

> **"AWS SAA-C03 Certification အောင်မြင်ရုံသာမက Production IT / Cloud Enterprise Genba (現場) တွင် ကျွမ်းကျင်သော Cloud Solutions Architect တစ်ဦးအဖြစ် ရပ်တည်နိုင်စေရန် Phase 0 မှ Phase 17 အထိ အခြေခံအကျဆုံးမှစ၍ လက်တွေ့ အသုံးချမှုအထိ အသေးစိတ် ရေးသားထားသော မာစတာသင်ရိုးလမ်းညွှန်"**

---

## ၁။ SAA-C03 စာမေးပွဲ အကျဉ်းချုပ် (Exam Blueprint Overview)

| အချက်အလက် | အသေးစိတ်ဖော်ပြချက် |
| :--- | :--- |
| **Exam Code** | SAA-C03 (AWS Certified Solutions Architect – Associate) |
| **Duration** | ၁၃၀ မိနစ် (Non-native English speakers များအတွက် +30 mins ESL Accommodation လျှောက်ထားနိုင်) |
| **Question Format** | Multiple Choice (အဖြေ ၁ ခုရွေး) & Multiple Response (အဖြေ ၂ ခု သို့မဟုတ် ၃ ခုရွေး) |
| **Total Questions** | ၆၅ ပုဒ် (Unscored Experimental မေးခွန်း ၁၅ ပုဒ် အပါအဝင်) |
| **Passing Score** | ၇၂၀ / ၁၀၀၀ မှတ် (Scaled Score: 100 to 1000) |
| **Official Domains** | ၄ ခု (Security 30%, Resiliency 26%, Performance 24%, Cost 20%) |

---

## ၂။ SAA-C03 Complete Course Curriculum (Phase 0 မှ Phase 17 အထိ အပြည့်အစုံ)

အောက်ပါ မာတိကာအတိုင်း Phase 0 မှ စတင်ကာ စနစ်တကျ အဆင့်ဆင့် လေ့လာနိုင်ပါသည်-

```
aws_saa_solutions_architect_real_work/
├── 00_Phase0_Foundations_Cloud_Networking_Linux.md
├── 01_Phase1_AWS_Core_Concepts_and_Global_Infrastructure.md
├── 02_Phase2_IAM_and_Security.md
├── 03_Phase3_VPC_and_Networking.md
├── 04_Phase4_Compute_EC2_Storage_AutoScaling.md
├── 05_Phase5_LoadBalancing_and_Route53_DNS.md
├── 06_Phase6_Storage_S3_EFS_and_Comparison.md
├── 07_Phase7_Databases_RDS_Aurora_DynamoDB.md
├── 08_Phase8_Performance_Architecture_Caching_CloudFront.md
├── 09_Phase9_Resilient_Architecture_and_Decoupling.md
├── 10_Phase10_Serverless_Architecture_Lambda_APIGateway.md
├── 11_Phase11_Application_Integration_and_Workflows.md
├── 12_Phase12_Monitoring_Operations_and_AWS_SSM.md
├── 13_Phase13_Backup_and_Disaster_Recovery.md
├── 14_Phase14_Cost_Optimization_and_FinOps.md
├── 15_Phase15_AWS_Well_Architected_Framework.md
├── 16_Phase16_Architecture_Decision_Making_Real_Work.md
├── 17_Phase17_SAA_Service_Comparison_Training.md
└── README.md
```

---

### အသေးစိတ် အခန်းခွဲများနှင့် သင်ခန်းစာများ:

1. 🔰 **[Phase 0 — SAA ကို မစခင် လိုအပ်သော အခြေခံအုတ်မြစ်များ (Foundations)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/00_Phase0_Foundations_Cloud_Networking_Linux.md)**
   - Cloud Computing ဆိုတာဘာလဲ၊ On-Prem vs Cloud၊ IaaS / PaaS / SaaS
   - Scalability, Elasticity, Availability, Reliability, Fault Tolerance, DR, Pay-as-you-go
   - Networking 101: IP, Public/Private IP, CIDR, Subnet, Port, TCP/UDP, DNS, HTTP/HTTPS, NAT, Routing, Firewall
   - User -> DNS -> Public IP -> Load Balancer -> Private Server -> DB Packet Flow
   - Linux Commands: `ls, cd, pwd, cp, mv, rm, cat, grep, find, ps, top, df, du, chmod, chown, systemctl, journalctl, curl, ssh`

2. 🌐 **[Phase 1 — AWS Core Concepts & Global Infrastructure](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/01_Phase1_AWS_Core_Concepts_and_Global_Infrastructure.md)**
   - Regions, Availability Zones (AZs), Edge Locations, Multi-AZ vs Multi-Region
   - Architect Mindset: "Application ကို ဘယ်နေရာမှာထားရင် availability, latency, cost ဘယ်လိုပြောင်းမလဲ?"
   - AWS Shared Responsibility Model (AWS တာဝန် vs Customer တာဝန် ခွဲခြမ်းစိတ်ဖြာမှု)

3. 🔐 **[Phase 2 — IAM & Security (Domain 1: 30%)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/02_Phase2_IAM_and_Security.md)**
   - IAM User, Group, Role, Policy (Managed vs Inline, Identity vs Resource-based, Least Privilege, MFA, STS)
   - `User -> Group -> Policy` vs `EC2 -> IAM Role -> S3` နှိုင်းယှဉ်ချက်
   - Authentication, Authorization, Encryption at rest & transit, Key management, Certificates
   - KMS, Secrets Manager, SSM Parameter Store, ACM, WAF, Shield, GuardDuty, Security Hub

4. 🔌 **[Phase 3 — VPC & Enterprise Networking](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/03_Phase3_VPC_and_Networking.md)**
   - VPC, CIDR, Subnets (Public vs Private), Route Tables, IGW, NAT Gateway, ENI, Elastic IP
   - Real Multi-AZ VPC Architecture (Internet -> IGW -> Public ALB -> Private App EC2s -> RDS)
   - Security Group (Stateful) vs Network ACL (Stateless)
   - VPC Peering, Transit Gateway, VPC Endpoints (Gateway vs Interface PrivateLink), VPN, Direct Connect

5. 💻 **[Phase 4 — Compute (EC2, Storage & Auto Scaling)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/04_Compute_EC2_Storage_AutoScaling.md)**
   - EC2 AMI, Instance Families, States, Key Pair, User Data, IMDSv2, Placement Groups, Dedicated Hosts
   - Pricing: On-Demand, Reserved Instances (RI), Savings Plans, Spot Instances
   - EBS Volumes (gp3, io2, st1, sc1), Snapshots, Encryption
   - Auto Scaling Groups (Launch Template, Min/Max/Desired, Health Checks, Target Tracking Scaling: Server 2 လုံးမှ 6 လုံးသို့ Scale လုပ်ခြင်း)

6. ⚖️ **[Phase 5 — Load Balancing & Route 53 DNS](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/05_Phase5_LoadBalancing_and_Route53_DNS.md)**
   - Application Load Balancer (ALB - Layer 7: Path/Host routing, Listeners, Target Groups)
   - Network Load Balancer (NLB - Layer 4: TCP/UDP, Ultra-low latency, Static IP) vs Classic LB (Legacy)
   - Route 53: Hosted Zones, Records (A, AAAA, CNAME, Alias, MX, TXT), Health Checks
   - Routing Policies: Simple, Weighted, Latency-based, Failover, Geolocation

7. 💾 **[Phase 6 — Storage (S3, EFS & Storage Comparison)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/06_Phase6_Storage_S3_EFS_and_Comparison.md)**
   - Amazon S3: Buckets, Objects, Keys, Versioning, Lifecycle Rules, Encryption, Multipart Upload, Presigned URLs
   - S3 Storage Classes: Standard, Intelligent-Tiering, Standard-IA, One Zone-IA, Glacier Instant/Flexible/Deep Archive
   - Amazon EFS: Shared NFSv4 filesystem, Multi-AZ, Linux workloads, Elastic scaling
   - **Crucial Exam Comparison: EBS vs EFS vs S3**

8. 🗄️ **[Phase 7 — Databases (RDS, Aurora & DynamoDB)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/07_Phase7_Databases_RDS_Aurora_DynamoDB.md)**
   - RDS: MySQL, PostgreSQL, MariaDB, Oracle, SQL Server, Subnet Groups, Parameter Groups, Backups
   - **Must-Compare: RDS Multi-AZ vs Read Replica**
   - Amazon Aurora: Cloud-Native Shared Storage across 3 AZs (6 copies), Serverless v2, Global Database
   - Amazon DynamoDB: Table, Items, Attributes, Partition Key, Sort Key, GSI, LSI, Query vs Scan, Streams
   - Core Concept: DynamoDB ကို RDS ကဲ့သို့ Relational Database အဖြစ် မစဉ်းစားရ!

9. ⚡ **[Phase 8 — Performance Architecture (Domain 3: 24%)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/08_Phase8_Performance_Architecture_Caching_CloudFront.md)**
   - In-Memory Caching: Amazon ElastiCache (Redis vs Memcached), Cache hit/miss, TTL, Invalidation
   - Amazon CloudFront CDN: Distribution, Origins, OAC (Origin Access Control), Cache Policy, HTTPS
   - Performance Diagnosis Scenario: "Website slow ဖြစ်နေတယ်။ DNS -> CloudFront -> ALB -> EC2 -> Redis -> DB ဘယ်လိုစဉ်းစားမလဲ?"

10. 🛡️ **[Phase 9 — Resilient Architecture & Decoupling (Domain 2: 26%)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/09_Phase9_Resilient_Architecture_and_Decoupling.md)**
    - High Availability, Multi-AZ, Health Checks, Failover, Fault Tolerance
    - Tight Coupling (`App A -> App B -> App C`) vs Loose Coupling (`App A -> SQS -> Worker`)
    - Amazon SQS (Standard vs FIFO, Visibility Timeout, DLQ, Long Polling)
    - Amazon SNS (Topic, Publisher, Subscriber, Pub/Sub Fan-out)
    - Amazon EventBridge (Events, Rules, Buses, Targets, Scheduled Tasks)

11. 🚀 **[Phase 10 — Serverless Architecture (Lambda & API Gateway)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/10_Phase10_Serverless_Architecture_Lambda_APIGateway.md)**
    - AWS Lambda: Runtimes, Handlers, Execution Roles, 15-min Timeout, Memory, Concurrency, Cold Starts
    - Amazon API Gateway: HTTP API vs REST API, Routes, Methods, Integrations, CORS, Throttling
    - Serverless Pattern: `Client -> API Gateway -> Lambda -> DynamoDB`

12. 🔄 **[Phase 11 — Application Integration & Workflows](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/11_Phase11_Application_Integration_and_Workflows.md)**
    - Microservices Decoupling & Serverless Event-Driven Principles
    - EventBridge Flow: `Order -> EventBridge -> Payment, Inventory, Notification`
    - AWS Step Functions: State Machines, Distributed Saga Pattern with Compensating Transactions

13. 📊 **[Phase 12 — Monitoring, Operations & AWS Systems Manager](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/12_Phase12_Monitoring_Operations_and_AWS_SSM.md)**
    - Amazon CloudWatch: Metrics, Logs, Alarms, Logs Insights
    - AWS CloudTrail: Management vs Data Events, User/API Auditing
    - AWS Systems Manager (SSM): Session Manager (No SSH Port 22 required), Run Command, Parameter Store, Patch Manager
    - Real Incident: "EC2 server CPU 95% ဖြစ်နေတယ်။ ဘယ် service နဲ့ ဘယ်လို စစ်မလဲ?"

14. 🛟 **[Phase 13 — Backup & Disaster Recovery (RPO & RTO)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/13_Phase13_Backup_and_Disaster_Recovery.md)**
    - EBS Snapshots, RDS Automated Backups & Snapshots, AWS Backup, S3 Versioning
    - RPO (Recovery Point Objective) & RTO (Recovery Time Objective)
    - DR Strategies: Backup & Restore, Pilot Light, Warm Standby, Multi-Site Active-Active
    - Scenario: "Database ပျက်သွားရင် ဘယ်လောက်အတွင်း ပြန်ရမလဲ?"

15. 💰 **[Phase 14 — Cost Optimization & FinOps (Domain 4: 20%)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/14_Phase14_Cost_Optimization_and_FinOps.md)**
    - AWS Cost Explorer, AWS Budgets, Cost and Usage Report (CUR), Cost Allocation Tags
    - Compute Right-sizing, Savings Plans, Spot, S3 Lifecycle
    - Data Transfer Costs & NAT Gateway charges avoidance via Gateway Endpoints
    - Architect Rule: "ဒီ architecture က အလုပ်လုပ်မလား?" နဲ့အတူ "ဒီ architecture က ဘယ်လောက်ကုန်မလဲ?"

16. 🏛️ **[Phase 15 — AWS Well-Architected Framework](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/15_Phase15_AWS_Well_Architected_Framework.md)**
    - The 6 Pillars: Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, Sustainability
    - Architect Mindset for Solutions Design

17. 🧠 **[Phase 16 — Architecture Decision Making (Real-World Genba)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/16_Phase16_Architecture_Decision_Making_Real_Work.md)**
    - Production Challenge: E-commerce Website, 100,000 Users, Image Uploads, Highly Available, Budget Constrained
    - Decision Breakdown: EC2 vs ECS? RDS vs Aurora? S3 vs EFS? ALB vs NLB? CloudFront? Redis? SQS? Multi-AZ?
    - "ဘာကြောင့် ဒီ service ကို ရွေးတာလဲ?" Architectural Rationale & Complete Blueprint

18. 🎯 **[Phase 17 — SAA Service Comparison Master Training (၁၃ မျိုး နှိုင်းယှဉ်ချက်)](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/17_Phase17_SAA_Service_Comparison_Training.md)**
    - Compute: EC2 vs ECS vs Lambda
    - Database: RDS vs Aurora vs DynamoDB
    - Storage: S3 vs EBS vs EFS
    - Load Balancing: ALB vs NLB
    - Messaging: SQS vs SNS vs EventBridge
    - Cache: Redis vs Memcached
    - DNS: Route 53 Routing Policies
    - CDN: CloudFront vs S3 Website
    - Access: IAM User vs Role
    - Network: Public vs Private Subnet
    - Availability: Multi-AZ vs Read Replica
    - Backup: Snapshot vs Backup
    - File sharing: EFS vs S3

---
*စတင်လေ့လာရန် Phase 0 သို့ သွားရောက်ပါ:* [00_Phase0_Foundations_Cloud_Networking_Linux.md](file:///Users/kyawwaiyan/Documents/my-Home-tech/AWS-Most-Used-Feature/aws_saa_solutions_architect_real_work/00_Phase0_Foundations_Cloud_Networking_Linux.md)
