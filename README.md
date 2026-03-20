# aws-ec2-lambda-automation
aws-ec2-lambda-automation with Boto3

# AWS EC2 Automation using Lambda & Boto3

## 📌 Objective
Automate EC2 instance start and stop using AWS Lambda based on tags.

---

## 🛠️ Services Used
- AWS EC2
- AWS Lambda
- IAM
- Python (Boto3)

---

## ⚙️ Setup Steps

### 1. EC2 Instances
- Created two EC2 instances
- Tagged as:
  - Auto-Stop
  - Auto-Start

### 2. IAM Role
- Created Lambda role
- Attached policy:
  - AmazonEC2FullAccess

### 3. Lambda Function
- Runtime: Python 3.x
- Used boto3 to:
  - Stop instances with tag `Auto-Stop`
  - Start instances with tag `Auto-Start`

### 4. Testing
- Triggered Lambda manually
- Verified instance states

---

## 📂 Project Structure
