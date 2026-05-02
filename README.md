# 🚀 Day 02 – Cloud Storage (AWS S3 / Azure Blob)

---

## 📌 Overview

On Day 02, I explored **Cloud Storage services**, focusing on how data is stored, managed, and accessed in the cloud using services like AWS S3 and Azure Blob Storage.

---

## ☁️ What is Cloud Storage?

Cloud storage allows users to store and retrieve data over the internet instead of using local storage.

---

## 🪣 Amazon S3 (Simple Storage Service)

Amazon S3 is an object storage service that provides high scalability, durability, and availability.

### 🔑 Key Features:

* Unlimited storage
* 99.999999999% durability
* Secure (IAM + policies)
* Versioning support
* Lifecycle management

---

## 📦 Core Concepts of S3

* **Bucket** → Container to store objects
* **Object** → File + metadata
* **Key** → Unique identifier for object
* **Region** → Physical location of bucket

---

## 🔐 Security in S3

* IAM Policies
* Bucket Policies
* Access Control Lists (ACLs)
* Encryption (at rest & in transit)

---

## 🔄 Storage Classes (S3)

* S3 Standard
* S3 Intelligent-Tiering
* S3 Standard-IA
* S3 Glacier
* S3 Glacier Deep Archive

---

## 🔵 Azure Blob Storage

Azure Blob Storage is Microsoft's object storage solution for storing large amounts of unstructured data.

### 🔑 Features:

* Highly scalable
* Secure access
* Lifecycle management
* Hot, Cool, Archive tiers

---

## ⚙️ Workflow Diagram

![Cloud Storage Workflow](diagram.png)

### (Text Version)

```
User Upload
   ↓
Cloud Storage (S3 / Blob)
   ↓
Data Stored in Buckets/Containers
   ↓
Access via API / Application
```

---

## 🌍 Real-World Use Cases

* Image & video storage
* Backup & disaster recovery
* Static website hosting
* Data lakes for ML

---

## 🧪 Mini Hands-On (AWS S3)

### Steps:

1. Create S3 bucket
2. Upload a file
3. Enable public access (for testing)
4. Access file via URL

---

## 🧠 What I Learned

* Object storage basics
* S3 core concepts
* Storage classes
* Cloud storage security

---

## 🚀 Next Step (Day 03)

* IAM (Identity & Access Management) deep dive
* Security concepts

---

## 📌 Author

**Sankar S**
Cloud & AI Learning Journey 🚀
