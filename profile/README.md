<p align="center">
  <img src="https://raw.githubusercontent.com/TocConsulting/.github/main/profile/assets/tocconsulting-logo.png" alt="TOC Consulting - Cloud. Secure. Scale." width="520" />
</p>

<p align="center">
Paris-based AWS consulting firm specializing in cloud security, architecture, and DevOps.<br/>
We build free, open-source tools that help teams secure and optimize their AWS environments.
</p>

<p align="center">
  <a href="https://tocconsulting.fr"><img src="https://img.shields.io/badge/Website-921CF6?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="#aws-security-scanners"><img src="https://img.shields.io/badge/Security_Scanners-181717?style=for-the-badge&logo=github&logoColor=white" alt="Security scanners" /></a>
  <a href="https://github.com/localemu/localemu"><img src="https://img.shields.io/badge/LocalEmu-0894ab?style=for-the-badge&logoColor=white" alt="LocalEmu" /></a>
</p>

<p align="center">
  <b><a href="https://tocconsulting.fr">tocconsulting.fr</a></b> |
  <b><a href="https://github.com/TocConsulting/aws-security-cards">AWS Security Cards</a></b> |
  <b><a href="https://github.com/localemu/localemu">LocalEmu Emulator</a></b> |
  <b><a href="https://fr.linkedin.com/in/tarekouldcheikh">LinkedIn</a></b>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/TocConsulting/.github/main/profile/assets/tocconsulting-in-action.png" alt="TocConsulting in action: open-source security scanners audit your AWS environment (EC2, S3, IAM, Lambda, RDS, ECS/EKS and more) with findings mapped to CIS, PCI DSS, HIPAA, SOC 2, ISO and GDPR" width="100%" />
</p>

**Open-source AWS security scanners, built from real client audits.**
We scan what we secure for clients every day: EC2, S3, IAM, Lambda, RDS,
ECS and EKS. Every finding is mapped to the compliance frameworks auditors
actually ask about: CIS, PCI DSS, HIPAA, SOC 2, ISO 27001, GDPR and NIST.

---

## Featured: LocalEmu

We maintain [**LocalEmu**](https://github.com/localemu/localemu), a free, open-source AWS cloud emulator, continued from the archived LocalStack community edition under the Apache 2.0 license. No account, no auth token, no sign-up. Point your existing AWS CLI, boto3, Terraform, or CDK at `localhost:4566` and build against AWS APIs from your laptop. Where it counts, the behavior is real, not stubbed: Lambda runs your code in the official AWS runtime images, EC2 instances are real containers on a real VPC, and RDS is a real PostgreSQL or MySQL you can connect to.

---

## AWS Security Scanners

Each scanner is a Python CLI available on PyPI and Docker Hub, with multi-threaded scanning, JSON, CSV and interactive HTML reports, and per-framework compliance mapping (CIS, AWS FSBP, PCI DSS, HIPAA, SOC 2, ISO 27001/27017/27018, GDPR, NIST 800-53).

| Project | What it scans |
|---|---|
| [s3-security-scanner](https://github.com/TocConsulting/s3-security-scanner) | S3 buckets: public access, weak bucket policies, missing encryption, cross-account replication exfiltration, CORS, and subdomain takeover risks |
| [ec2-security-scanner](https://github.com/TocConsulting/ec2-security-scanner) | EC2 and its network: IMDSv2, security groups, EBS encryption, public AMIs and snapshots, patch compliance, and UserData secret detection |
| [iam-security-scanner](https://github.com/TocConsulting/iam-security-scanner) | IAM: privilege escalation paths, confused-deputy trust, MFA enforcement, key rotation, password policy, and least-privilege analysis |
| [rds-security-scanner](https://github.com/TocConsulting/rds-security-scanner) | RDS and Aurora: storage encryption, TLS enforcement, public access, IAM auth, backups, deletion protection, and Multi-AZ posture |
| [ecs-eks-security-scanner](https://github.com/TocConsulting/ecs-eks-security-scanner) | ECS and EKS: privileged containers, secrets in task definitions, public endpoints, control-plane logging, IAM role separation, and ECR hygiene |
| [lambda-security-scanner](https://github.com/TocConsulting/lambda-security-scanner) | Lambda: deprecated runtimes, secrets in environment variables, public function URLs, permissive execution roles, and code signing |

## Security Tools & Research

| Project | Description |
|---|---|
| [iam-activity-tracker](https://github.com/TocConsulting/iam-activity-tracker) | Serverless auditing of IAM, STS, and Console sign-in activity across all regions: real-time SNS security alerts, S3 + Athena analytics, and event retention beyond CloudTrail's 90-day window |
| [aws-security-cards](https://github.com/TocConsulting/aws-security-cards) | Security reference cards for major AWS services: attack vectors, misconfigurations, enumeration commands, privilege escalation, persistence techniques, and defense recommendations, in Markdown, HTML and PDF |
| [litellm-supply-chain-attack-analysis](https://github.com/TocConsulting/litellm-supply-chain-attack-analysis) | Malware analysis of the March 2026 LiteLLM supply chain attack: the real compromised packages detonated in an isolated EC2 lab, the decoded multi-stage payload, captured C2 traffic, and complete IOCs |
| [aws-security-agent-from-zero-to-hero](https://github.com/TocConsulting/aws-security-agent-from-zero-to-hero) | Hands-on research and a 16-article series on AWS Security Agent, AWS's AI pentesting service: a purpose-built vulnerable app lab, real CloudWatch/CloudTrail logs, detection-rate measurement, and attempts to trick and attack the agent itself |

## Cloud & Developer Tools

| Project | Description |
|---|---|
| [localemu](https://github.com/localemu/localemu) | Free, open-source AWS cloud emulator. Run AWS services locally and point your existing AWS CLI, boto3, Terraform, or CDK at `localhost:4566`. Apache 2.0, no account, no token |
| [awsmap](https://github.com/TocConsulting/awsmap) | Fast AWS resource mapping and inventory across all services and regions: SQLite-backed scan history, SQL and natural-language queries, drift detection, waste detection, and tag compliance |
| [cryptex](https://github.com/TocConsulting/cryptex) | CLI password generator with AWS Secrets Manager, HashiCorp Vault, and OS keychain integrations, compliance templates (NIST, PCI DSS, OWASP), and TOTP support |
| [aws-helper-scripts](https://github.com/TocConsulting/aws-helper-scripts) | Collection of standalone AWS security, cost-optimization, and inventory scripts, each with a deployable Lambda version |

## Labs & Learning

| Project | Description |
|---|---|
| [chaos-on-aws](https://github.com/TocConsulting/chaos-on-aws) | Companion code for our "Chaos Engineering on AWS" article series on the [TOC Consulting blog](https://tocconsulting.fr/blog): deployable Terraform labs using AWS Fault Injection Service, from single-instance failures to full AZ outages and multi-Region DR |

## Applications

| Project | Description |
|---|---|
| [cognito-api](https://github.com/TocConsulting/cognito-api) | Authentication and user management API built on AWS Cognito: MFA, passkeys, full user lifecycle, one-command Terraform deployment. Full documentation at [cognito-api.com](https://cognito-api.com) |
| [enclave](https://github.com/TocConsulting/enclave) | Serverless secure file sharing on AWS: direct-to-S3 uploads, expiring presigned share links, optional per-user KMS encryption, React front end, one-command Terraform |

---

## What we do

- **Security audits**: comprehensive AWS security assessments, IAM audits, and compliance mapping (CIS, PCI DSS, HIPAA, SOC 2, ISO 27001, GDPR)
- **Cloud architecture**: secure-by-design, scalable AWS infrastructures and multi-account strategies
- **Infrastructure as Code**: Terraform and CloudFormation automation
- **DevOps & CI/CD**: pipeline design, containerization, and deployment automation

---

<p align="center">
  <a href="https://tocconsulting.fr"><img src="https://img.shields.io/badge/Website-921CF6?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="mailto:tarek@tocconsulting.fr"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://fr.linkedin.com/in/tarekouldcheikh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center">Paris, France · <a href="https://tocconsulting.fr">tocconsulting.fr</a></p>
