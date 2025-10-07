## Cloud Computing – Revision Notes

## What is Cloud Computing
- Cloud computing delivers computing services (servers, storage, databases, networking, software) over the internet.  
- Enables **on-demand access**, **scalability**, and **pay-as-you-go** pricing.  
- Removes the need to own physical infrastructure.

## IaaS vs PaaS vs SaaS
- **IaaS (Infrastructure as a Service):** Provides virtualized hardware resources. Example: Azure VM.  
- **PaaS (Platform as a Service):** Offers ready platforms for development and deployment. Example: Azure App Service.  
- **SaaS (Software as a Service):** Delivers fully managed applications via the web. Example: Microsoft 365.

## Shared Responsibility Model
- Cloud provider and customer share security and management responsibilities.  
- **Provider:** Responsible for physical infrastructure, network, and hypervisor.  
- **Customer:** Manages data, access, and app-level configurations.  
- The division depends on service type (IaaS → user manages more; SaaS → provider manages most).

## Cloud Deployment Models
- **Public Cloud:** Services offered over the internet, shared infrastructure (e.g., Azure, AWS).  
- **Private Cloud:** Dedicated to a single organization; more control, higher cost.  
- **Hybrid Cloud:** Combination of public and private; balances flexibility and security.

## Benefits of Cloud
- **Availability:** Global data centers ensure uptime and reliability.  
- **Scalability:** Resources scale up/down automatically based on demand.  
- **Elasticity:** Pay only for what is used; quick adaptation to workload changes.  
- **Cost Efficiency & Security:** Reduced capital expenses with built-in compliance tools.

## Azure Pricing
- **Azure Pricing Calculator:** Estimates monthly costs for services.  
- **TCO (Total Cost of Ownership) Calculator:** Compares on-premises vs cloud expense.  
- Factors influencing price: location, resource size, usage duration, and type of service.

## Azure Resource Hierarchy
- **Management Group → Subscription → Resource Group → Resource**  
- Management groups: organize multiple subscriptions.  
- Resource groups: logical containers for resources.  
- Each resource belongs to one resource group only.

## Azure Portal Overview
- Web-based interface for managing and monitoring all Azure resources.  
- Allows navigation through dashboard, resource creation, settings, and monitoring tools.  
- Supports CLI, PowerShell, and REST APIs for automation.

## Data Centers, Regions, and Availability Zones
- **Region:** Geographical location with one or more data centers.  
- **Availability Zone (AZ):** Physically separate zone within a region; independent power, networking.  
- AZs improve fault tolerance and disaster recovery.

## Creating a Virtual Machine (VM) in Azure
- Choose specs: OS, size, region, and pricing tier.  
- Configure network, disks, and authentication (SSH or password).  
- Review and create → Azure allocates required compute and storage resources automatically.

