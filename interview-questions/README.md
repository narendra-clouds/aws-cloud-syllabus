# 🎯 AWS Interview Questions (Project-Based)

This section contains **important AWS interview questions with simple, professional answers**.  
All questions are based on **real-world projects and scenarios**, not just theory.

---

## 🔰 Beginner-Level Interview Questions

### 1. What AWS services did you use in your beginner projects?
I used services like **S3, EC2, IAM, and CloudWatch**.  
For example, I hosted a static website using **S3**, deployed a web server on **EC2**, managed access using **IAM**, and monitored resources using **CloudWatch**.

---

### 2. How did you host a static website on AWS?
I used **Amazon S3**.  
I uploaded website files to an S3 bucket, enabled static website hosting, set bucket permissions, and accessed the site using the S3 endpoint.

---

### 3. What is an EC2 instance?
EC2 is a **virtual server in AWS**.  
It allows us to run applications without managing physical hardware.

---

### 4. How did you secure your EC2 instance?
I used **Security Groups** to allow only required ports like **SSH (22)** and **HTTP (80)**.  
I also used **key pairs** instead of passwords for secure login.

---

### 5. What is IAM and why is it important?
IAM controls **who can access AWS resources and what actions they can perform**.  
It helps follow the **principle of least privilege** and improves security.

---

## 🟡 Intermediate-Level Interview Questions

### 6. What is the difference between Security Groups and NACLs?
Security Groups work at the **instance level** and are **stateful**.  
NACLs work at the **subnet level** and are **stateless**.

---

### 7. What is Auto Scaling and why is it used?
Auto Scaling automatically **increases or decreases EC2 instances** based on traffic.  
It improves **availability** and **cost efficiency**.

---

### 8. How does a Load Balancer work?
A Load Balancer distributes incoming traffic across multiple EC2 instances.  
This improves **performance, fault tolerance, and availability**.

---

### 9. What is a VPC?
A VPC is a **virtual private network in AWS** where you can launch resources securely.  
It allows control over IP ranges, subnets, routing, and security.

---

### 10. What monitoring services did you use?
I used **Amazon CloudWatch** to monitor metrics like CPU usage, create alarms, and view logs.  
This helped detect issues early.

---

## 🔴 Job-Level Interview Questions

### 11. Explain a 3-tier architecture you built on AWS.
I built a **3-tier architecture** with:
- **ALB** in the public subnet  
- **EC2 instances** in private subnets  
- **RDS** for the database  

This improves **security, scalability, and separation of concerns**.

---

### 12. How did you design a secure VPC architecture?
I used **public and private subnets**, **NAT Gateway** for outbound internet access, **Security Groups**, **NACLs**, and restricted IAM permissions.

---

### 13. What is serverless and when should we use it?
Serverless means AWS manages servers for you.  
You only focus on code.  
I used **Lambda + API Gateway** for event-driven workloads where scaling and cost efficiency were important.

---

### 14. How did you automate infrastructure creation?
I used **Infrastructure as Code** tools like **CloudFormation or Terraform**.  
This allowed repeatable, version-controlled infrastructure deployment.

---

### 15. How do you handle logging and auditing in AWS?
I used **CloudTrail** for auditing API calls and **CloudWatch Logs** for application logs.  
This helps with **security, compliance, and troubleshooting**.

---

### 16. How do you optimize AWS costs?
I optimized costs by:
- Using **Auto Scaling**
- Choosing correct instance types
- Stopping unused resources
- Using **Free Tier / Reserved Instances**
- Monitoring usage via **Cost Explorer**

---

## ⭐ Common Interview Closing Question

### 17. How do you explain your AWS projects to recruiters?
I explain:
1. **Problem statement**
2. **AWS services used**
3. **Architecture design**
4. **Security & scalability**
5. **Challenges and solutions**

This shows **real understanding**, not just theory.

---

📌 **Tip:**  
Always relate your answers to **projects you actually built**.  
Interviewers prefer **practical explanations over definitions**.
