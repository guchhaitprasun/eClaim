# eClaim Case Study – Root Repository


## 📑 Problem Statement
YCompany, with over 200M customers, is facing inefficiencies in its **manual claims processing system**:
- Claims take weeks to settle, causing customer dissatisfaction.  
- No real-time tracking for customers.  
- Manual processes for adjustors, surveyors, and workshops increase delays.  
- Lack of analytics, fraud detection, and reporting capabilities.  

The goal of this case study is to **modernize claims management** with a **scalable, secure, and cloud-ready digital solution** that delivers faster settlements, real-time transparency, and integration with partner ecosystems.  

---

## 🖼️ Architecture & Diagrams

### Architecture Diagram
![Architecture](./diagrams/Architecture.png)

### Deployment Diagram
![Deployment](./diagrams/Deployment.png)

### CI/CD Workflow
![CI/CD Workflow](./diagrams/CICD.png)

---

## 📂 POC Repositories

This root repository references multiple service and application repositories that form the Proof of Concept (POC).  

| Repository | Description | Current Status |
|------------|-------------|----------------|
| [eclaim-frontend](https://github.com/guchhaitprasun/eClaim-frontend) | Angular SPA (Customer Portal) | ![Static Badge](https://img.shields.io/badge/Web%20UI-Scaffolded-green) <br> ![Static Badge](https://img.shields.io/badge/Not%20Deployed-red)|
| [eclaim-mobile](https://github.com/guchhaitprasun/eClaim-mobile) | React Native Mobile App | ![Static Badge](https://img.shields.io/badge/Mobile%20UI-Scaffolded-green) <br> ![Static Badge](https://img.shields.io/badge/Not%20Deployed-red) |
| [eclaim-claims-service](https://github.com/guchhaitprasun/eClaim-claim-service) | .NET 8 Microservice (Claims Management) | ![Static Badge](https://img.shields.io/badge/Service-Scaffolded-green) <br>  ![Static Badge](https://img.shields.io/badge/Not%20Deployed-red) |
| [eclaim-notification-service](https://github.com/guchhaitprasun/eClaim-notification-service) | Node.js Microservice (Notifications) | ![Static Badge](https://img.shields.io/badge/ServiceI-Scaffolded-green)  <br> ![Static Badge](https://img.shields.io/badge/Not%20Deployed-red) |
| Other services (to be added) | Future integrations (Car Rental, Workshop APIs, etc.) | ⏳ Planned |


⚠️ **Note:** The POC is **partially implemented** and not fully deployed due to lack of Azure subscriptions. Local scaffolding exists in these repositories.  

---

## 📧 Contact
For queries regarding this submission:  
**Prasun Guchhait** – prasun.guchhait@nagarro.com  
