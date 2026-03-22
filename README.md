# AWS-ec2-lambda-automation
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
- Runtime: Python 3.14
- Used boto3 to:
  - Stop instances with tag `Auto-Stop`
  - Start instances with tag `Auto-Start`

### 4. Testing
- Triggered Lambda manually
- Verified instance states
  
### 5. Snapshots for Refrense.
- Manually power on EC2 Instances for verification pourpose.
<img width="1484" height="167" alt="image" src="https://github.com/user-attachments/assets/b4b80e23-22ee-428b-bc1f-849c91913dc8" />


- Post Lambada run works perfectly as per instructions given.
<img width="1490" height="154" alt="image" src="https://github.com/user-attachments/assets/bcd2d230-ee9d-404b-8e6e-d7869af4144f" />





---

## 📂 Project Structure
