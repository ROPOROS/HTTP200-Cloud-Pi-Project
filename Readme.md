
# ☁️ CareerTN – Cloud Platform

> A cloud-native multi-tenant SaaS platform built to connect users and professionals, supported by an OpenStack-based private cloud infrastructure.

---

## 🧩 Tech Stack
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![OpenStack](https://img.shields.io/badge/OpenStack-ED1944?logo=openstack&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)

---

## 📚 Table of Contents
1. [Overview](#overview)
2. [Architecture](#architecture)
3. [Web Application](#web-application)
4. [Infrastructure](#infrastructure)
5. [Deployment](#deployment)
6. [Monitoring](#monitoring)
7. [Achievements](#achievements)
8. [Team](#team)

---

## Overview
CareerTN is a **cloud-based hiring platform** designed to connect clients and professionals through a multi-tenant architecture.  
The project includes both the **SaaS web application** and its **private cloud infrastructure**, developed by the **HTTP200 team at ESPRIT**.

---

## Architecture
**Frontend:** Angular  
**Backend:** Spring Boot REST APIs  
**Database:** MySQL  
**Containerization:** Docker  
**Orchestration:** Kubernetes (via OpenStack Magnum)  
**Infrastructure as Code:** Terraform & Ansible  
**Monitoring:** Prometheus + Grafana  

## 🧱 Architecture

<p align="center">
  <img src="/architecture.png" alt="Architecture" width="750">
</p>


---

## Web Application
- User registration and authentication  
- Multi-tenant architecture for clients and professionals  
- Service listings, job requests, and reviews  
- JWT-based API security  
- Dockerized frontend and backend  

**Setup:**
```bash
# Frontend
cd frontend
npm install
npm run build

# Backend
cd backend
./mvnw clean package
