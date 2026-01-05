# Vincent Omondi Owuor

**AWS Certified Cloud Practitioner | Architecting Resilient Systems for 20K+ Concurrent Users**

Building fault-tolerant distributed systems with Failure-First Architecture. Focused on solving production-scale challenges: network partitions, race conditions, and consistency trade-offs. Hands-on with AWS infrastructure, serverless patterns, and IT support.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/owuorviny109/owuorviny109/main/github-metrics.svg" alt="Metrics" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=owuorviny109&color=blue&style=for-the-badge" alt="Profile Views" />
  
  <a href="https://github.com/owuorviny109?tab=followers">
    <img src="https://img.shields.io/github/followers/owuorviny109?style=for-the-badge&logo=github&label=Followers&color=orange" alt="Followers" />
  </a>

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=owuorviny109&theme=github-compact&hide_border=true&area=true" alt="Activity Graph" />
</p>

---

## Systems Thinking in Action

### [M-Pesa E-commerce Integration](https://github.com/owuorviny109/mpesa-ecommerce-blueprint)
**System Challenge:** Ensuring payment consistency in a distributed system with high transaction failure rates and network partitions.

**Architecture:**
- Saga Pattern for dual-write operations between Inventory and Payment Gateway
- Idempotency Keys to prevent duplicate charges during network replays
- Optimistic Locking to handle high-concurrency checkout events without database deadlocks

**Result:** 100% data consistency during simulated network failures; zero double-charges recorded.

**Tech:** Node.js, M-Pesa Daraja API, Distributed Payment Systems

---

### [SafariSmart Kenya](https://safari-smart.vercel.app/)
**System Challenge:** Building a fault-tolerant interface that never crashes despite upstream AI service instability.

**Architecture:**
- Circuit Breaker patterns to fallback to cached itineraries when error rate exceeded 15%
- Validation Middleware using Zod schemas to reject and retry malformed JSON responses
- Hybrid Cloud Strategy (Render + AWS S3) reducing operational costs by 40%

**Result:** System uptime maintained at 99.9% even during AI provider outages.

**Tech:** Django, Google Gemini AI, AWS S3, PostgreSQL, Circuit Breakers

---

### [EduCore Academic Suite](https://github.com/owuorviny109/EduCore-Suite)
**System Challenge:** Maintaining system availability and data integrity under burst load (5000+ concurrent registrations).

**Architecture:**
- ACID-compliant transaction isolation to solve race conditions
- Materialized Views optimizing O(N) queries to O(1) lookups
- Strategic Database Indexing for high-volume write operations

**Result:** Enrollment latency reduced by 60%, database CPU utilization dropped from 95% to 40% during peak load.

**Tech:** ASP.NET MVC, SQL Server, High-Concurrency Systems

---

### [Terraform AWS 3-Tier Infrastructure](https://github.com/owuorviny109/terraform-aws-web-tier-infra)
**System Challenge:** Achieving zero-downtime deployments across multiple regions while maintaining data consistency.

**Architecture:**
- Multi-AZ Deployment for high availability and fault tolerance
- Infrastructure as Code using Terraform for repeatable deployments
- Enterprise-grade Network Security with VPC, private subnets, NAT Gateways

**Tech:** Terraform, AWS (VPC, EC2, RDS), Multi-Region Architecture

---

## Architecture & Distributed Systems

**Core Competencies**

![Distributed Systems](https://img.shields.io/badge/Distributed_Systems-CAP_Theorem-purple?style=for-the-badge)
![Event-Driven](https://img.shields.io/badge/Event_Driven-Architecture-blue?style=for-the-badge)
![Microservices](https://img.shields.io/badge/Microservices-Saga_Patterns-green?style=for-the-badge)
![Circuit Breakers](https://img.shields.io/badge/Circuit_Breakers-Fault_Tolerance-orange?style=for-the-badge)

**Distributed Patterns**

![Idempotency](https://img.shields.io/badge/Idempotency-Keys-red?style=for-the-badge)
![Eventual Consistency](https://img.shields.io/badge/Eventual_Consistency-Models-yellow?style=for-the-badge)
![Rate Limiting](https://img.shields.io/badge/Rate_Limiting-Strategies-teal?style=for-the-badge)
![Optimistic Locking](https://img.shields.io/badge/Optimistic_Locking-Concurrency-pink?style=for-the-badge)

---

## Cloud & Infrastructure

**AWS Expertise**

![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-Serverless-orange?style=for-the-badge&logo=amazon-aws&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-NoSQL-blue?style=for-the-badge&logo=amazon-dynamodb&logoColor=white)
![S3](https://img.shields.io/badge/S3-Storage-green?style=for-the-badge&logo=amazon-s3&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-CDN-red?style=for-the-badge&logo=amazon-aws&logoColor=white)

**DevOps & IaC**

![Terraform](https://img.shields.io/badge/Terraform-IaC-purple?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-blue?style=for-the-badge&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI/CD-Automation-green?style=for-the-badge&logo=github-actions&logoColor=white)
![Vercel Edge](https://img.shields.io/badge/Vercel_Edge-CDN-black?style=for-the-badge&logo=vercel&logoColor=white)

---

## Implementation Stack

**Backend & Data**

![Python](https://img.shields.io/badge/Python-Language-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-Framework-092E20?style=for-the-badge&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Runtime-green?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge&logo=postgresql&logoColor=white)

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-Language-blue?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-Library-blue?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-Framework-black?style=for-the-badge&logo=nextdotjs&logoColor=white)

---

## Certifications

<p align="left">
  <a href="https://www.credly.com/users/vincent-omondi.43720300">
    <img src="https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-orange?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Oracle_Cloud-Infrastructure_Foundations-red?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/Oracle-AI_Foundations-blue?style=for-the-badge&logo=oracle&logoColor=white" />
</p>

---

## Connect & Collaborate

<p align="center">
  <a href="https://www.linkedin.com/in/owuor-vincent-38b2b02ba">
    <img src="https://img.shields.io/badge/LinkedIn-Professional_Network-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://owuorvincent.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-Systems_Architecture-black?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="mailto:owuorvincent069@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.credly.com/users/vincent-omondi.43720300">
    <img src="https://img.shields.io/badge/Credly-Verify_Credentials-orange?style=for-the-badge&logo=credly&logoColor=white" />
  </a>
</p>

<p align="center">
  <a href="https://owuorvincent.vercel.app/Vincent_Omondi_cv.html">
    <img src="https://img.shields.io/badge/Download_Resume-Systems_Focus-8A2BE2?style=for-the-badge" />
  </a>
</p>
