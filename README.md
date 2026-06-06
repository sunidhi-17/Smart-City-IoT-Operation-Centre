# Smart City IoT Operations Center on Microsoft Azure

## Overview

The Smart City IoT Operations Center is a cloud infrastructure project built on Microsoft Azure to simulate enterprise-scale smart city operations. The project demonstrates how IoT devices, applications, databases, and administrators can interact securely within a scalable cloud environment using a 3-tier architecture.

## Features

* 3-Tier Virtual Machine Architecture
* Secure Virtual Network (VNet) Design
* Network Security Groups (NSGs) for Traffic Control
* Microsoft Entra ID-based Authentication and RBAC
* Azure Blob Storage for Data Storage
* Azure Load Balancer for Traffic Distribution
* Azure Application Gateway for Layer-7 Routing
* Recovery Services Vault for Backup Management
* Azure CLI for Infrastructure Management

## Architecture

### Tier 1 – Gateway Layer

* Receives incoming IoT device and sensor traffic.
* Acts as the entry point to the system.

### Tier 2 – Application Layer

* Processes and routes IoT data.
* Hosts application services.

### Tier 3 – Database Layer

* Stores processed information and operational data.
* Maintains data persistence and availability.

### Administration Layer

* Dedicated VM for monitoring, management, and administrative tasks.

## Azure Services Used

* Azure Virtual Machines
* Azure Virtual Network (VNet)
* Network Security Groups (NSG)
* Azure Load Balancer
* Azure Application Gateway
* Azure Blob Storage
* Microsoft Entra ID
* Role-Based Access Control (RBAC)
* Recovery Services Vault
* Azure CLI

## Project Objectives

* Design a secure cloud network architecture.
* Implement identity and access management using RBAC.
* Deploy and manage virtual machines.
* Configure load balancing and application routing.
* Demonstrate enterprise-level cloud infrastructure practices.
* Simulate a scalable Smart City IoT ecosystem.

## Learning Outcomes

Through this project, I gained practical experience in:

* Microsoft Azure Infrastructure Deployment
* Cloud Networking and Security
* Identity and Access Management
* Load Balancing and Application Routing
* Backup and Recovery Management
* Azure CLI Administration
* Enterprise Cloud Architecture Design

## Tech Stack

**Cloud Platform:** Microsoft Azure

**Compute:** Azure Virtual Machines (Ubuntu Server 22.04)

**Networking:** Azure VNet, NSG, Load Balancer, Application Gateway

**Identity & Security:** Microsoft Entra ID, RBAC

**Storage:** Azure Blob Storage

**Management:** Azure CLI, Recovery Services Vault

## Future Enhancements

* Real-time IoT sensor integration
* Azure Monitor and Log Analytics integration
* Automated deployment using Infrastructure as Code (Terraform/Bicep)
* CI/CD pipeline implementation
* Dashboard for real-time city monitoring

## Author

**Sunidhi Sharma**

Bachelor of Technology – Computer Science and Engineering

Lovely Professional University

