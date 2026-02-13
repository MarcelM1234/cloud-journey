# Cloud Journey (Public Proof Log)

**Why I'm here**
I’m transitioning into cloud to build a durable career, solve real problems, and create
options for my family.

**My Focus (next 90 days)**
- AWS foundations (IAM, S3, EC2, CloudWatch)
- IaC with Terraform
- Documenting every build (README, screenshots, LinkedIn)

**Week 1 – Identity & First Wins**
- Set up GitHub + LinkedIn for cloud visibility
- Wrote this public proof log
- Next up: S3 + IAM “Public Access Problem” lab
  
**Projects (live/soon)**

**How I document**
Each project includes: problem → approach → commands/code → screenshots →
lessons learned → what I'd do differently.

**Contact/Connect**
- LinkedIn: <www.linkedin.com/in/marcel-m-a93718177>
- Notes: If you’re hiring for junior cloud/security roles, I’m documenting proof every week
  
Posted(2/7/2026)


## Problem Statement
A public e-commerce site (CloudMart) experienced downtime when images stored in
S3 became inaccessible due to misconfigured bucket permissions.

## Investigation Process
- Reproduced the Access Denied issue.
- Reviewed S3 public access settings.
- Compared IAM roles and bucket policies.

## Solution
Implemented a least-privilege S3 bucket policy allowing controlled public object
access.

## Validation
- Tested object URLs in a browser,  verified public access.
- Confirmed no unauthorized uploads possible.
  
## Result
Product images restored.  
Permissions secured.  
Cost: $0 (AWS Free Tier).  

## Skills Highlighted
AWS S3 • IAM • Cloud Security • Troubleshooting • Documentation

(Posted)2/8/2026



AWS IAM Admin User Setup 

Overview

In this module, I implemented identity security best practices in AWS by creating an administrative IAM user and discontinuing daily use of the root account. This exercise demonstrates foundational cloud security and access management skills.

Objectives

- Avoid using the AWS root account for routine work
- Create a dedicated IAM admin user
- Assign appropriate permissions securely
- Enable console access
- Verify successful login with the new identity

Steps Performed

1️. Root Login 
- Logged into AWS using the root account (one final time)
- Navigated to IAM Dashboard

2️. Create IAM Admin User
- Created a new IAM user
- Enabled AWS Management Console access
- Set initial password and required reset on first login

3️. Assign Permissions
- Attached policy:
- AdministratorAccess
- Verified policy attachment

4️. Secure Root Account
- Logged out of root account
- Reserved root for account ownership/emergency use only

5️. Validate Access
- Logged in using new IAM admin credentials
- Confirmed successful access to services

Outcome
- IAM administrative user created
- AdministratorAccess policy applied
- Successful login using IAM identity
-Root account no longer used for daily tasks

