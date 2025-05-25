# Cloud Calculator Project

This project analyzes the infrastructure needs and cost models of deploying a physician office management system on public cloud providers (GCP, AWS, Azure). It compares VM configurations and pricing for Development, QA, and Production environments.

## 📘 Context
Prepared by **Ahmad Hussein**  
Master 1 – Data Science  
Saint-Joseph University, Beirut  
Course: *Cloud and Digital Transformation*  
Instructor: Dr. Marlène Seif

## 🏥 Use Case
The system is designed to support medium-sized physician offices in France with:
- 15 physicians, 3 nurses
- HIPAA compliance requirements
- High availability & low-latency demand (<200ms)
- Budget-sensitive pricing (no long-term contracts)

## ☁️ Cloud Infrastructure
The system requires:
- **3 Environments**: Development, QA, Production
- **VM Configurations**:
  - Vary by environment (CPU, RAM, uptime)
  - Compared across GCP, AWS, and Azure
- **Pricing Models**: Pay-as-you-go evaluated monthly

## 🔍 Recommendation
Based on VM cost only, **Google Cloud Platform (GCP)** offers the best pricing fit.

## 🗂 File
- `Cloud_Calculator_Project.pdf` – Full slide-based project documentation 

---

## 🧠 Key Concepts
- **Deployment Model**: Public Cloud
- **Service Model**: SaaS (Software as a Service)

