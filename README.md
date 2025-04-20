# 📦 Databases in Practice — AWS RDS Deployment

## ⏱ Total Time: 01:00:42  
**Project Type:** Cloud Database Practice Lab  
**Goal:** Improve database **operational efficiency**, **availability**, and **performance efficiency** using AWS RDS advanced features.

---

## 🚀 Project Overview

This lab focuses on deploying and optimizing a **relational database** using **Amazon RDS (Relational Database Service)**. The objective is to explore how AWS can enhance the performance, availability, and manageability of database systems through features like:

- Multi-AZ deployments  
- Automated backups  
- Read replicas

---

## 🎯 Key Objectives

### ✅ Learn about AWS database offerings
- Understand the use cases of **Amazon RDS**, **Amazon Aurora**, and other managed database services.

### ✅ Launch an Amazon RDS instance
- Create a primary database using **Amazon RDS** (e.g., MySQL/PostgreSQL engine).
- Use instance type: `db.t3.medium` for primary setup.

### ✅ Configure Multi-AZ deployment
- Enable **Multi-AZ** for automatic failover and high availability.

### ✅ Configure Amazon RDS backups
- Set up **automated backups** with a defined retention period.
- Enable **automatic snapshots** to restore data easily in case of failure.

### ✅ Create a Read Replica
- Set up a **read replica** using `db.t3.xlarge` to offload read traffic and enhance performance.

---

## 🛠 Technologies Used

- **Amazon Web Services (AWS)**
  - Amazon RDS
  - EC2 (optional connection for validation)
  - VPC + Security Groups (for DB access configuration)
- **Database Engine**: MySQL / PostgreSQL (based on use-case)
- **Instance Types**:  
  - Primary: `db.t3.medium`  
  - Read Replica: `db.t3.xlarge`

---

## 📈 Outcomes & Benefits

- ✅ Improved **availability** via Multi-AZ
- ✅ Increased **read performance** using read replica
- ✅ Enhanced **reliability** with automated backups
- ✅ Hands-on experience with managed database operations on AWS



