# Microservices 

Automate CI/CD Pipelines, Monitoring, Metrics & Logging for two microservices based apps

- Laravel App
- Sock Shop App

---

## Project Overview

In this project, you will apply **ALL** the skills you have acquired throughout your learning in ALTSCHOOL AFRICA SCHOOL OF ENGINEERING - CLOUD TRACK to automate the Continuous Delivery of two microservices based app including Monitoring, Metrics, and Logging.

We deploy our microservices-based architecture on Kubernetes and we need to create
a clear IaaC (Infrastructure as Code) deployment to be able to deploy our services in a
fast manner

---

## Setup

- Provision a webapp of your choosing with nginx/httpd frontend proxy and a database
  (mongo, postgresql etc) backend.

- Provision the Socks Shop example microservice application -
  https://microservices-demo.github.io/

---

## Project Tasks

- Everything needs to be deployed using an Infrastructure as Code approach
- In your solution please emphasize readability, maintainability and DevOps
  methodologies. We expect a clear way to recreate your setup and will evaluate the
  project decisions on:  
  · Deploy pipeline  
  · Metrics  
  · Monitoring  
  · Logging  
  · Use Prometheus as a monitoring tool  
  · Use Ansible or Terraform as the configuration management tool  
  · You can use an IaaS provider of your choice.  
  · The application should run on Kubernetes

---

### CircleCI Continuous Delivery Pipeline

![pipeline](image/pipeline.jpg)

### Build

![build](image/build-image.jpg)

### EKS Cluster

![eks-cluster](image/create-cluster.jpg)

### Deploying both apps

![deploying-larave](image/deploy-laravel.jpg)
![deploying-sock-shop](image/deploy-sock-shop.jpg)

### Monitoring, Metrics, and Logging

![monitoring-metrics](image/monitoring-and-logging.jpg)

### Nginx Ingress

![nginx](image/ingress.jpg)

### laravel app page

![laravel](image/laravel-page.jpg)

### sock shop app page

![sock-shop](image/sock-shop-app.jpg)

### loki loggings for the laravel app

![loki-laravel](image/loki-logging-for-laravel.jpg)

### loki loggings for the sock shop app

![loki-sock-shop](image/loki-logging-for-sock-shop.jpg)

### prometheus monitoring

![prometheus-monitoring](image/prometheus-overview.jpg)

### prometheus cpu usage

![prometheus-monitoring](image/prometheus-cpu-usage.jpg)

### prometheus memory usage

![prometheus-monitoring](image/prometheus-mem-usage.jpg)
