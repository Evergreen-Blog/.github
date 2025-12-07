![evergreen_blog_logo](https://github.com/user-attachments/assets/d9b4152c-0c4a-42af-b949-1bd0ee842fcd)

# 📗 Evergreen Blog
## 0. Introduction
### 📌 Overview

Evergreen Blog is a highly available blog platform designed to remain accessible at all times without outages or interruptions. Built on modern infrastructure technologies such as Docker, Kubernetes, and Microsoft Azure, the platform enables anyone to create and share content quickly, reliably, and at scale.

### 🎯 Background

Traditional personal blogs and small-to-medium platforms often struggle during sudden traffic spikes or unexpected server failures. As a result, users may face service downtime or slow response times.
Evergreen Blog was planned to solve these operational risks and deliver a “never-down blog service” that remains stable under any circumstances.

### 👥 Target Users

Developers & IT professionals: those who want a stable, production-grade tech blog

Companies & startup teams: teams needing reliable spaces for release notes, announcements, or internal content

Content creators: users who require steady posting and uninterrupted communication with their audience

### 🧩 Problems We Address

Downtime caused by server failures

Slow response during traffic surges

Service interruptions during updates

Operational risks from inconsistent deployment environments

### 🌱 Core Values of Evergreen Blog

Always-on service: automatic recovery ensures uninterrupted access even in failure scenarios

Global scalability: fast access from anywhere using Azure’s global infrastructure

Operational efficiency: container-based architecture enables effortless deployment and scaling

High stability: zero-downtime operation powered by Azure services and Kubernetes

## 1. Key Features & Infrastructure Overview
- 🌍 Global Reliability with Azure Cloud

  Evergreen Blog leverages Microsoft Azure’s globally distributed data centers to deploy services across multiple regions. Even if one region experiences an outage, traffic is automatically routed to another, ensuring seamless and consistent accessibility.

- 🐳 Fast & Flexible Operations with Container Technology

  Each service component is packaged as a Docker container, enabling consistent environments across development, testing, and production. This allows rapid feature delivery, quick recovery in case of failures, and straightforward scaling as user traffic increases.

- ☸️ Automated Management & Recovery with Kubernetes

  The platform uses Azure Kubernetes Service (AKS) to orchestrate and manage the containers. AKS automatically adjusts resource allocation based on traffic changes, handles container failures, and ensures users always experience an uninterrupted service.

- 📈 Real-Time Monitoring & Rapid Issue Response

  Evergreen Blog enhances reliability by using Azure Monitor, AKS built-in monitoring, and various logging tools to continuously track system performance and detect anomalies. This enables early detection, swift response, and stable service delivery at all times.
  
## High-Level Architecture
![구성도(추상)](https://github.com/user-attachments/assets/5dcf067f-e83b-4df1-a60b-d83c71433a1d)
