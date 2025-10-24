# Kubernetes Homelab

This repository contains my personal **Kubernetes homelab** for learning, experimentation, and hands-on practice with DevOps and cloud-native technologies. It serves as a playground to explore real-world scenarios, test applications, and continuously improve my skills as a DevOps engineer.

## Overview

The homelab includes a variety of components commonly used in production environments:

- **MinIO** – S3-compatible object storage  
- **Prometheus & Alertmanager** – Monitoring and alerting  
- **Grafana** – Dashboards and visualization  
- **NGINX & Ingress Controllers** – Routing and load balancing  
- **ArgoCD** – GitOps-based continuous delivery  
- **Test Applications** – Sample apps like Guestbook and a mini Super Mario game  

The setup is **actively evolving**, with new tools and experiments added over time. Resources are currently configured for a **single-node cluster on my old laptop with 8 GB of RAM**, but the plan is to expand to multiple nodes using Raspberry Pi devices, enabling larger-scale experiments, replication, and scaling practice.

## Purpose

- Practice **full Kubernetes ecosystem usage**, including deployment, scaling, resource management, networking, storage, monitoring, and GitOps workflows
- Experiment with **GitOps workflows** and continuous delivery  
- Gain hands-on experience with **monitoring, logging, and observability**  
- Build a **portfolio of practical DevOps projects**  

## Usage

Some components, such as **Prometheus, Grafana, and NGINX**, are installed via **Helm charts**, while the rest are managed and deployed by **ArgoCD**, providing a GitOps workflow.

---

Author: Antonio Zdravac
LinkedIn: https://www.linkedin.com/in/antonio-%C5%BEdravac-96b030b4/

