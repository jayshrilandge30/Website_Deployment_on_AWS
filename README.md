# Website Deployment on AWS using Custom VPC and Monitoring

##  Project Overview
This project demonstrates hosting a scalable and highly available website on **AWS** by creating a **Custom VPC** with **Auto Scaling**, **Application Load Balancer**, and monitoring via **CloudWatch**. It also integrates **Simple Notification Service (SNS)** for real-time alerts and notifications, ensuring continuous availability, scalability, and operational visibility.

🔗 **GitHub Repository:** [Website_Deployment_on_AWS](https://github.com/jayshrilandge30/Website_Deployment_on_AWS)

---

##  Features
- **Custom VPC** for secure and isolated networking
- **Auto Scaling** for handling varying traffic loads
- **Application Load Balancer** for distributing requests
- **CloudWatch Monitoring** with alarms and dashboards
- **AWS SNS** for instant notifications
- **Secure Database Deployment** in private subnet

---

## 🛠 Project Implementation Steps

### 1️⃣ Create a Custom VPC
![Custom VPC Creation](images/screenshot1.png)

### 2️⃣ Create Subnets (Public & Private)
![Subnet Configuration](images/screenshot2.png)

### 3️⃣ Create an Internet Gateway
![Internet Gateway Setup](images/screenshot3.png)

### 4️⃣ Create a NAT Gateway
![NAT Gateway Setup](images/screenshot4.png)

### 5️⃣ Create Route Tables (Public & Private)
![Route Tables Setup](images/screenshot5.png)

### 6️⃣ Create Security Group (Ports 22, 80)
![Security Group Rules](images/screenshot6.png)

### 7️⃣ Create an SNS Topic
![SNS Topic Creation](images/screenshot7.png)

### 8️⃣ Create an Empty Target Group
![Target Group Setup](images/screenshot8.png)

### 9️⃣ Create an Application Load Balancer
![ALB Creation](images/screenshot9.png)

### 🔟 Create Launch Template
![Launch Template Setup](images/screenshot10.png)

### 1️⃣1️⃣ Create an Auto Scaling Group
![Auto Scaling Group](images/screenshot11.png)

### 1️⃣2️⃣ Create CloudWatch Alarms
![CloudWatch Alarms](images/screenshot12.png)

### 1️⃣3️⃣ Create CloudWatch Dashboard
![Monitoring Dashboard](images/screenshot13.png)

### 1️⃣4️⃣ Attach Domain to Load Balancer
![DNS Mapping](images/screenshot14.png)

### 1️⃣5️⃣ Launch Database in Private Subnet
![DB Instance Setup](images/screenshot15.png)

---

##  Website Outputs

### Server & Database
- **Deployed Server Instances**  
  ![Deployed Server Instances](images/screenshot16.png)
- **Database Table in Private Subnet**  
  ![Database Table](images/screenshot17.png)
- **SNS Notification Received in Gmail**  
  ![SNS Notification](images/screenshot18.png)

### Public IP Outputs
- **Webserver 1 Output**  
  ![My_Project_Webserver1](images/screenshot19.png)
- **Webserver 2 Output**  
  ![My_Project_Webserver2](images/screenshot20.png)

### Load Balancer & Domain Outputs
- **Application Output via Load Balancer DNS**  
  ![Load Balancer Output](images/screenshot21.png)
- **Final Deployed Website Home Page with Domain**  
  ![Home Page](images/screenshot22.png)
- **About Page via Domain**  
  ![About Page](images/screenshot23.png)
- **Our Menu Section**  
  ![Our Menu](images/screenshot24.png)
- **Customer Reviews Section**  
  ![Customer Reviews](images/screenshot25.png)
- **Contact Page**  
  ![Contact Page](images/screenshot26.png)

---

##  Project Architecture
![AWS Project Architecture](images/screenshot27.png)

---

##  Summary
- Hosted a **scalable & highly available website** on AWS using a **Custom VPC**  
- Implemented **Auto Scaling** and **Application Load Balancer** for traffic management  
- Enabled **CloudWatch Monitoring** with alarms and dashboards  
- Integrated **SNS Notifications** for real-time alerts  
- Secured the architecture by placing the **database in a private subnet**  

---

##   Author
**Jayshri Landge**  
📍 Aurangabad, India  
🔗 [GitHub Profile](https://github.com/jayshrilandge30)
