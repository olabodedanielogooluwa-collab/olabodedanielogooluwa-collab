# Hi, I'm HeroTheGreat

**Aspiring Cloud Security Engineer | Self-directed, hands-on training in AWS, Linux, and Terraform**

I'm building toward a Junior Cloud Security Engineer role through a structured 12-week program combining Linux administration, networking fundamentals, Infrastructure as Code, and incident diagnostics, documented in public, week by week.

7 Terraform-built AWS lab environments across Weeks 6-9, from EC2 and IAM with MFA enforcement to a VPC with public/private subnets and a NAT Gateway. I then broke the networking three ways (NACL, VPC peering, subnet placement) and traced each failure with Reachability Analyzer.

I don't just complete tutorials. Every week includes a queue of deliberately broken systems I have to diagnose, fix, and write up, so the skills are tested under failure, not just demonstrated in a happy path.

## What I'm Working With

**Cloud Platforms:** AWS (EC2, S3, IAM, CloudTrail, VPC, NAT Gateway, VPC Peering, NACLs, Security Groups)

**Infrastructure as Code:** Terraform

**Systems & Networking:** Linux (Debian-based) · Bash · SSH hardening · DNS/DHCP/ARP fundamentals · VPC routing · Reachability Analyzer · Cisco Packet Tracer

**Security Fundamentals:** IAM least-privilege and MFA enforcement · CloudTrail log analysis · S3 bucket policy design · Network segmentation (public/private subnets, NACLs, security groups) · SSH key auth & hardening · Security incident diagnostics

**In Progress:** AWS Cloud Practitioner (CLF-C02) · CompTIA Security+ (foundational study) · Python/boto3

## Currently Learning

- AWS Cloud Practitioner certification (CLF-C02): FreeCodeCamp course + AWS Skill Builder
- Deeper Terraform patterns (parameterized configs, remote state)
- Python/boto3 for automating AWS checks
- Project 03: Secure VPC + Threat Model

## Featured Work

**VPC Architecture + Incident Response (Week 9):** Built a VPC from scratch in Terraform with public and private subnets, an Internet Gateway, a NAT Gateway, and separate route tables. Then broke it three ways and traced each failure: a stateless NACL dropping return traffic, a VPC peering route on only one side, and a database deployed into the public subnet. Biggest finding: moving the database to the private subnet closed the exposure before the security group was touched. [Read the writeup](https://github.com/olabodedanielogooluwa-collab/cloud-security-portfolio/tree/main/week-9)

**IAM + CloudTrail (Week 8):** IAM groups, users, and a least-privilege policy managed in Terraform, plus an MFA-enforcement policy and multi-region CloudTrail. Traced an AccessDenied error to the MFA policy instead of the S3 policy using IAM Policy Simulator. [Read the writeup](https://github.com/olabodedanielogooluwa-collab/cloud-security-portfolio/tree/main/week-8)

**EC2 + Terraform Deployment:** Live EC2 instance provisioned end-to-end with Terraform (security group, key pair, and instance wired together), with Apache running and reachable at a public IP. Debugged real provisioning failures along the way: provider version mismatches, Free Tier instance-type changes, duplicate resource conflicts.

**S3 Bucket Security Project:** S3 bucket built with ownership controls and an account-restricted bucket policy. Includes a documented incident where a 403 error was traced to Public Access Block settings and confirmed as correct, expected behavior via an authenticated access test: not just "fixed," understood.

**Weekly Incident Queue:** Each week includes 2-3 deliberately broken systems (file permission failures, runaway processes, service outages, misconfigured IAM and networking) diagnosed and documented from first principles.

## How I Work

I document everything as I go: weekly runbooks with what broke, how I diagnosed it, and what I'd do differently. The goal isn't to look finished; it's to make the reasoning visible.

## Open to

Junior Cloud Security Engineer roles · Cloud Support · DevOps-adjacent security work

📍 Nigeria
🐦 Writing on X: [@HeroTGreat](https://x.com/iam_HeroTGreat)
<!--
**olabodedanielogooluwa-collab/olabodedanielogooluwa-collab** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
