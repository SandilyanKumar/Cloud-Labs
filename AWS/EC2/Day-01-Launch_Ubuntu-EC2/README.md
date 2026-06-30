# Lab-01: Launch an Ubuntu EC2 Instance

## Objective

The objective of this lab is to launch an Ubuntu EC2 instance in AWS and understand the basic configuration options required during instance creation.

---

## Prerequisites

- AWS Account
- IAM User with EC2 permissions
- Basic understanding of AWS Console

---

## AWS Services Used

- Amazon EC2
- Amazon VPC
- Security Group
- Key Pair

---

## Lab Environment

S.No	Parameter	           Value
1	Operating System	    Ubuntu Server 24.04 LTS
2	Instance Type	        t2.micro
3	Region                	ap-south-1 (Mumbai)
4	Storage	                8 GB gp3
5	Authentication	        Key Pair
6	Network             	VM VPC

---

## Step-by-Step Procedure

### Step 1

Login to the AWS Management Console.

---

### Step 2

Navigate to

**Services → EC2**

---

### Step 3

Click

**Launch Instance**

---

### Step 4

Provide the instance details

- Name
- Ubuntu Server 24.04 LTS
- t2.micro

---

### Step 5

Create or select an existing Key Pair.

---

### Step 6

Create a Security Group.

Allow:

- SSH (Port 22)

Source:

- My IP

---

### Step 7

Keep the default storage configuration.

- 8 GB gp3

---

### Step 8

Review all settings.

Click

**Launch Instance**

---

### Step 9

Wait until the instance state changes to

**Running**

---

## Verification

Verify the following:

- EC2 Instance State = Running
- Status Checks = 2/2 Passed
- Public IPv4 Address assigned

---

## Result

Successfully launched an Ubuntu EC2 instance in AWS.

---

## Learning Outcome

After completing this lab, I learned:

- How to launch an EC2 instance
- How to choose an AMI
- How to select an instance type
- How to create a Key Pair
- How to configure a Security Group
- How to verify the instance status

---

## Screenshots

- Launch Instance Wizard
- EC2 Configuration
- Running Instance
- EC2 Dashboard