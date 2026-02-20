# 📗 Study Guide for Microsoft Azure Fundamentals exam (AZ-900)

This guide is intended to provide a list of pre-selected materials to help anyone starting in the  cloud computing career and/or discovering Azure be ready to the AZ-900 exam.

> **_NOTE:_**  A version in Brazilian-Portuguese is [available here](https://github.com/ricmmartins/guia-estudo-az900)

*Last update on February 20, 2026*

## 📋 Learning Path from [Microsoft Learn](https://aka.ms/learn) for Exam AZ-900

* [Introduction to Cloud Infrastructure: Describe cloud concepts](https://learn.microsoft.com/en-us/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/)
* [Introduction to Cloud Infrastructure: Describe Azure architecture and services](https://learn.microsoft.com/en-us/training/paths/azure-fundamentals-describe-azure-architecture-services/)
* [Introduction to Cloud Infrastructure: Describe Azure management and governance](https://learn.microsoft.com/en-us/training/paths/describe-azure-management-governance/)


## 📝 Skills Measured - [Obtained from the official link](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900#skills-measured-as-of-january-14-2026)

### 💡 Describe cloud concepts (25–30%)

#### Describe cloud computing
* Define cloud computing
  * [What is cloud computing?](https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-fundamentals/what-is-cloud-computing)
* Describe the shared responsibility model
  * [Shared responsibility in the cloud](https://docs.microsoft.com/en-us/azure/security/fundamentals/shared-responsibility)
* Define cloud models, including public, private, and hybrid
  * [Different types of cloud model](https://learn.microsoft.com/en-us/training/modules/fundamental-azure-concepts/types-of-cloud-computing) 
* Identify appropriate use cases for each cloud model
  * [What are the different types of cloud computing services?](https://azure.microsoft.com/en-us/overview/types-of-cloud-computing/)
  * [Describe different cloud services](https://docs.microsoft.com/en-us/learn/modules/fundamental-azure-concepts/categories-of-cloud-services)
  * [Building blocks of the cloud](https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-admin-overview/04-building-blocks)
* Describe the consumption-based model
  * [Cloud computing is a consumption-based model](https://docs.microsoft.com/en-us/learn/modules/fundamental-azure-concepts/benefits-of-cloud-computing)
* Compare cloud pricing models
  * [Cloud use cases: CapEx, OpEx](https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-admin-overview/07-economics)
  * [Capital expenses vs. operating expenses](https://docs.microsoft.com/en-us/learn/modules/fundamental-azure-concepts/benefits-of-cloud-computing)
  * [Cloud computing is a consumption-based model](https://docs.microsoft.com/en-us/learn/modules/fundamental-azure-concepts/benefits-of-cloud-computing)
* Describe serverless
  * [What is serverless computing](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-serverless-computing/)

#### Describe the benefits of using cloud services
* Describe the benefits of high availability and scalability in the cloud
  * [Describe the benefits of high availability and scalability in the cloud](https://learn.microsoft.com/en-us/training/modules/describe-benefits-use-cloud-services/2-high-availability-scalability-cloud)
* Describe the benefits of reliability and predictability in the cloud
  * [Describe the benefits of reliability and predictability in the cloud](https://learn.microsoft.com/en-us/training/modules/describe-benefits-use-cloud-services/3-reliability-predictability-cloud)   
* Describe the benefits of security and governance in the cloud
  * [Describe the benefits of security and governance in the cloud](https://learn.microsoft.com/en-us/training/modules/describe-benefits-use-cloud-services/4-security-governance-cloud)
* Describe the benefits of manageability in the cloud
  * [Describe the benefits of manageability in the cloud](https://learn.microsoft.com/en-us/training/modules/describe-benefits-use-cloud-services/5-manageability-cloud)

#### Describe cloud service types
* Describe infrastructure as a service (IaaS)
  * [What is IaaS?](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-iaas/)
* Describe platform as a service (PaaS)
  * [What is PaaS?](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-paas/)
* Describe software as a service (SaaS)
  * [What is SaaS?](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-saas/)
* Identify appropriate use cases for each cloud service type (IaaS, PaaS, and SaaS)
  * [Describe cloud service types](https://learn.microsoft.com/en-us/training/modules/describe-cloud-service-types/)
  
### 💡 Describe Azure architecture and services (35–40%)

#### Describe the core architectural components of Azure
* Describe Azure regions, region pairs, and sovereign regions
  * [Azure regions, availability zones, and region pairs](https://learn.microsoft.com/en-us/training/modules/azure-architecture-fundamentals/regions-availability-zones)
* Describe availability zones
  * [Regions and availability zones](https://learn.microsoft.com/en-us/azure/reliability/overview#regions-and-availability-zones)
  * [What is resiliency in Azure?](https://azure.microsoft.com/en-us/resources/azure-resiliency-infographic/)
* Describe Azure datacenters
  * [Azure Global Infrastructure](https://azure.microsoft.com/en-us/explore/global-infrastructure/)
  * [What are Azure regions and availability zones?](https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview)
  * [Microsoft Datacenter Virtual Tour](https://datacenters-wp-production.azurewebsites.net/)
  * [We live in Cloud](https://news.microsoft.com/stories/microsoft-datacenter-tour/)
* Describe Azure resources and resource groups
  * [What is an Azure resource?](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works#what-is-an-azure-resource)
  * [What is an Azure resource group?](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works#what-is-an-azure-resource-group)
* Describe availability zone?
  * [Availability zones](https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview#availability-zones)
* Describe subscriptions
  * [What is an Azure subscription?](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works#what-is-an-azure-subscription)
* Describe management groups
  * [Azure management groups](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/organize-subscriptions?source=recommendations#azure-management-groups)
* Describe the hierarchy of resource groups, subscriptions, and management groups
  * [Hierarchy of management groups and subscriptions](https://learn.microsoft.com/en-us/azure/governance/management-groups/overview#hierarchy-of-management-groups-and-subscriptions)
  * [Management levels and hierarchy](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/organize-resources#management-levels-and-hierarchy)

#### Describe Azure compute and networking services
* Compare compute types, including container instances, virtual machines (VMs), and functions
  * [Containers vs. virtual machines](https://learn.microsoft.com/en-us/virtualization/windowscontainers/about/containers-vs-vm) 
  * [Choose an Azure compute service](https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree)
* Describe VM options, including Azure Virtual Machines, Azure Virtual Machine Scale Sets,
availability sets, and Azure Virtual Desktop
  * [Explore Azure compute services](https://learn.microsoft.com/en-us/training/modules/azure-compute-fundamentals/)
  * [What is an availability set?](https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview#what-is-an-availability-set)
* Describe resources required for virtual machines
  * [Required resources for IaaS Virtual Machines](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-virtual-machines/2-compile-a-checklist-for-creating-a-vm) 
* Describe application hosting options, including the Web Apps feature of Azure App Service,
containers, and virtual machines
  * [Explore Azure compute services](https://learn.microsoft.com/en-us/training/modules/azure-compute-fundamentals/)
* Describe virtual networking, including the purpose of Azure Virtual Networks, Azure virtual
subnets, peering, Azure DNS, Azure VPN Gateway, and Azure ExpressRoute
  * [Explore Azure networking services](https://learn.microsoft.com/en-us/training/modules/azure-networking-fundamentals/)
* Define public and private endpoints
  * [Difference between service endpoint and private endpoint](https://stackoverflow.com/questions/73769449/azure-difference-between-service-endpoint-and-private-endpoint-in-simple-terms)

#### Describe Azure storage services
* Compare Azure storage services
  * [Explore Azure Storage services](https://learn.microsoft.com/en-us/training/modules/azure-storage-fundamentals/)
* Describe storage tiers
  * [Hot, cool, and archive access tiers for blob data](https://learn.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview)
  * [Understand Blob access tiers](https://learn.microsoft.com/en-us/training/modules/azure-storage-fundamentals/azure-storage-tiers)
* Describe redundancy options
  * [Azure storage redundancy](https://learn.microsoft.com/en-us/azure/storage/common/storage-redundancy)
* Describe storage account options and storage types
  * [Types of storage accounts](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview#types-of-storage-accounts)
* Identify options for moving files, including AzCopy, Azure Storage Explorer, and Azure File Sync
  * [Choose an Azure solution for data transfer](https://learn.microsoft.com/en-us/azure/storage/common/storage-choose-data-transfer-solution)
  * [Transfer data with AzCopy and file storage](https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-files)
  * [Small dataset, low to moderate network bandwidth](https://learn.microsoft.com/en-us/azure/storage/common/storage-solution-small-dataset-low-moderate-network#recommended-options)
  * [Large dataset, moderate to high network bandwidth](https://learn.microsoft.com/en-us/azure/storage/common/storage-solution-large-dataset-moderate-high-network?#high-network-bandwidth-1-gbps---100-gbps)
* Describe migration options, including Azure Migrate and Azure Data Box
  * [Choose an Azure solution for data transfer](https://learn.microsoft.com/en-us/azure/storage/common/storage-choose-data-transfer-solution)
  * [Azure Storage Migration Tools Comparison](https://learn.microsoft.com/en-us/azure/storage/solution-integration/validated-partners/data-management/migration-tools-comparison)
  * [What is Azure Data Box?](https://learn.microsoft.com/en-us/azure/databox/data-box-overview)

#### Describe Azure identity, access, and security
* Describe directory services in Azure,  Microsoft Entra ID and Microsoft Entra Domain Services
  * [What is Entra ID](https://learn.microsoft.com/en-us/entra/fundamentals/what-is-entra)
  * [Compare Active Directory to Microsoft Entra IDy](https://learn.microsoft.com/en-us/entra/fundamentals/compare
  * [Associate or add an Azure subscription to your Microsoft Entra tenant](https://learn.microsoft.com/en-us/entra/fundamentals/how-subscriptions-associated-directory)
  * [Set up a new Microsoft Entra tenant]([https://learn.microsoft.com/en-us/azure/active-directory/develop/quickstart-create-new-tenant](https://learn.microsoft.com/en-us/entra/identity-platform/quickstart-create-new-tenant))
  * [Microsoftr Entra](https://learn.microsoft.com/en-us/entra/)
  * [Meet Microsoft Entra](https://www.microsoft.com/en-us/security/blog/?p=114039)
  * [What is Entra Domain Services?](https://learn.microsoft.com/en-us/entra/identity/domain-services/overview)
* Describe authentication methods in Azure, including single sign-on (SSO), multifactor authentication, and passwordless
  * [Authentication vs. authorization](https://learn.microsoft.com/en-us/entra/identity-platform/authentication-vs-authorization)
  * [What is Microsoft Entra authentication?](https://learn.microsoft.com/en-us/entra/identity/authentication/overview-authentication)
* Describe external identities and guest access in Azure
  * [Introduction to Microsoft Entra External ID](https://learn.microsoft.com/en-us/entra/external-id/external-identities-overview)
  * [Guest users in Entra]([https://learn.microsoft.com/en-us/azure/active-directory/external-identities/what-is-b2b#collaborate-with-any-partner-using-their-identities](https://learn.microsoft.com/en-us/entra/external-id/what-is-b2b#collaborate-with-any-partner-using-their-identities))
* Describe Microsoft Enrta Conditional Access
  * [What is Conditional Access?](https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview)
* Describe Azure role-based access control (RBAC)
  * [What is Azure role-based access control (Azure RBAC)?](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview)
* Describe the concept of Zero Trust
  * [Zero Trust Security](https://learn.microsoft.com/en-us/azure/security/fundamentals/zero-trust)
* Describe the purpose of the defense in depth model
  * [Microsoft Azure's defense in depth approach to cloud vulnerabilities](https://azure.microsoft.com/en-us/blog/microsoft-azures-defense-in-depth-approach-to-cloud-vulnerabilities/)
  * [Defense in depth](https://learn.microsoft.com/en-us/training/modules/azure-well-architected-security/2-defense-in-depth)
* Describe the purpose of Microsoft Defender for Cloud
  * [What is Microsoft Defender for Cloud?](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-cloud-introduction)

### 💡 Describe Azure management and governance (30–35%)

#### Describe cost management in Azure
* Describe factors that can affect costs in Azure
  * [Azure Pricing](https://azure.microsoft.com/en-us/pricing/)
  * [Bandwith pricing](https://azure.microsoft.com/en-us/pricing/details/bandwidth/)
* Compare the Pricing calculator and the Total Cost of Ownership (TCO) calculator
  * [Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)
  * [The Cost of Ownership (TCO) Calculator](https://azure.microsoft.com/en-us/pricing/tco/calculator/)
* Describe the Azure Cost Management and Billing tool
  * [What is Cost Management + Billing?](https://learn.microsoft.com/en-us/azure/cost-management-billing/cost-management-billing-overview)
  * [How to optimize your cloud investment with Cost Management](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices)
  * [Plan to manage Azure costs](https://learn.microsoft.com/en-us/azure/cost-management-billing/understand/plan-manage-costs)
* Describe the purpose of tags
  * [Use tags to organize your Azure resources and management hierarchy](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources?tabs=json)
  * [Tagging decision guide](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming-and-tagging-decision-guide#tagging-decision-guide)

#### Describe features and tools in Azure for governance and compliance
* Describe the purpose of Microsoft Purview in Azure
  * [Learn about Microsoft Purview](https://learn.microsoft.com/en-us/purview/purview)  
* Describe the purpose of Azure Policy
  * [What is Azure Policy](https://learn.microsoft.com/en-us/azure/governance/policy/overview)
  * [Introduction to Azure Policy](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-policy/) 
* Describe the purpose of resource locks
  * [Lock your resources to protect your infrastructure](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources)


#### Describe features and tools for managing and deploying Azure resources
* Describe the Azure portal
  * [Choose the best tools for managing and configuring your Azure environment](https://learn.microsoft.com/en-us/training/modules/management-fundamentals/)
  * [What is the Azure Portal?](https://learn.microsoft.com/en-us/azure/azure-portal/azure-portal-overview)
* Describe Azure Cloud Shell, including Azure CLI and Azure PowerShell
  * [Overview of Azure Cloud Shell](https://learn.microsoft.com/en-us/azure/cloud-shell/overview)
  * [What is the Azure CLI?](https://learn.microsoft.com/pt-br/cli/azure/what-is-azure-cli)
  * [What is Azure PowerShell?](https://learn.microsoft.com/en-us/powershell/azure/what-is-azure-powershell?view=azps-9.6.0)
* Describe the purpose of Azure Arc
 * [Azure ARC Overview](https://learn.microsoft.com/en-us/azure/azure-arc/overview)
* Describe infrastructure as code (IaC)
  * [What is infrastructure as code](https://learn.microsoft.com/en-us/devops/deliver/what-is-infrastructure-as-code)
* Describe Azure Resource Manager and Azure Resource Manager templates (ARM templates)
  * [What is Azure Resource Manager?](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview)
  * [What are ARM templates?](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)
  * [Deploy and manage resources in Azure by using JSON ARM templates](https://learn.microsoft.com/en-us/training/paths/deploy-manage-resource-manager-templates/)

#### Describe monitoring tools in Azure
* Describe the purpose of Azure Advisor
  * [Azure Advisor Overview](https://learn.microsoft.com/en-us/azure/advisor/advisor-overview)
  * [Introduction to Azure Advisor](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-advisor/)
* Describe Azure Service Health
  * [What uis Azure Service Health?](https://learn.microsoft.com/en-us/azure/service-health/overview)
  * [Intro to Azure Service Health](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-service-health/)
* Describe Azure Monitor, including Log Analytics, Azure Monitor alerts, and Application Insights
  * [Choose the best monitoring service for visibility, insight, and outage mitigation](https://learn.microsoft.com/en-us/training/modules/monitoring-fundamentals/)
  * [Describe monitoring tools in Azure](https://learn.microsoft.com/en-us/training/modules/describe-monitoring-tools-azure/)
  * [Monitor app performance](https://learn.microsoft.com/en-us/training/modules/monitor-app-performance/)
  * [Improve incident response with alerting on Azure](https://learn.microsoft.com/en-us/training/modules/incident-response-with-alerting-on-azure/)

## Extras

* [AZ-900 Overview](https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/)
* [Certification poster](http://aka.ms/traincertposter)
* [Free Azure account sign-up](https://azure.microsoft.com/en-us/free/)
* [Exam environment simulation](https://aka.ms/examdemo)
* [Azure Infrastructure Map](http://infrastructuremap.microsoft.com/)
* [Cloud administration basics](https://docs.microsoft.com/en-us/learn/paths/cmu-admin/)
  * [Foundations of cloud computing for administrators](https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-admin-overview/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Provision and manage cloud services](https://docs.microsoft.com/en-us/learn/modules/cmu-provision-cloud-services/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Secure your cloud resources with access control](https://docs.microsoft.com/en-us/learn/modules/cmu-secure-cloud-resources/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Virtualize resources in the cloud](https://docs.microsoft.com/en-us/learn/modules/cmu-virtualization/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Scale your cloud resources with elasticity](https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-elasticity/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Automate cloud resource management](https://docs.microsoft.com/en-us/learn/modules/cmu-orchestration/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Monitor cloud resources](https://docs.microsoft.com/en-us/learn/modules/cmu-monitor-cloud-resources/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)

## Show your support
Give the project's GitHub repository a ⭐️ if this content helped you!
