# Table of Contents
- [List of Terraform Challenges](#list-of-terraform-challenges)
    - [Challenge 1: Provision a Virtual Network](#challenge-1-provision-a-virtual-network)
    - [Challenge 2: Deploy a Virtual Machine](#challenge-2-deploy-a-virtual-machine)
    - [Challenge 3: Configure Azure Storage Account](#challenge-3-configure-azure-storage-account)
    - [Challenge 4: Set Up Azure Key Vault](#challenge-4-set-up-azure-key-vault)
    - [Challenge 5: Implement Azure App Service](#challenge-5-implement-azure-app-service)
    - [Challenge 6: Configure Azure SQL Database](#challenge-6-configure-azure-sql-database)
    - [Challenge 7: Deploy Azure Kubernetes Service (AKS)](#challenge-7-deploy-azure-kubernetes-service-aks)
    - [Challenge 8: Set Up Azure DNS Zone](#challenge-8-set-up-azure-dns-zone)
    - [Challenge 9: Implement Azure Load Balancer](#challenge-9-implement-azure-load-balancer)
    - [Challenge 10: Set Up Azure Function App](#challenge-10-set-up-azure-function-app)
    - [Challenge 11: Configure Azure Application Gateway](#challenge-11-configure-azure-application-gateway)
    - [Challenge 12: Set Up Azure Cosmos DB](#challenge-12-set-up-azure-cosmos-db)
    - [Challenge 13: Implement Azure Traffic Manager](#challenge-13-implement-azure-traffic-manager)
    - [Challenge 14: Configure Azure Redis Cache](#challenge-14-configure-azure-redis-cache)
    - [Challenge 15: Set Up Azure Logic Apps](#challenge-15-set-up-azure-logic-apps)
- [Resources](#resources)

# Terraform-Challenge-AZ
Collection of Technical challenges using terraform in Azure  

Use open source terraform modules such as  
 - [Microsoft Repositories](https://github.com/orgs/Azure/repositories?q=terraform-azurerm)  

The use of Terraform modules is not required, but is highly encouraged. 

## List of Terraform Challenges

### Challenge 1: Provision a Virtual Network
- **Objective**: Create a virtual network with subnets.
- **Resources**: `azurerm_virtual_network`, `azurerm_subnet`
- **Steps**:
    1. Define the virtual network resource.
    2. Add subnet configurations.
    3. Apply the configuration.

### Challenge 2: Deploy a Virtual Machine
- **Objective**: Deploy a virtual machine in Azure.
- **Resources**: `azurerm_virtual_machine`, `azurerm_network_interface`, `azurerm_network_security_group`
- **Steps**:
    1. Create a network interface.
    2. Define the virtual machine resource.
    3. Attach the network interface to the virtual machine.

### Challenge 3: Configure Azure Storage Account
- **Objective**: Set up a storage account with a blob container.
- **Resources**: `azurerm_storage_account`, `azurerm_storage_container`
- **Steps**:
    1. Define the storage account resource.
    2. Create a blob container within the storage account.

### Challenge 4: Set Up Azure Key Vault
- **Objective**: Create an Azure Key Vault and add secrets.
- **Resources**: `azurerm_key_vault`, `azurerm_key_vault_secret`
- **Steps**:
    1. Define the key vault resource.
    2. Add secrets to the key vault.

### Challenge 5: Implement Azure App Service
- **Objective**: Deploy an App Service with a web app.
- **Resources**: `azurerm_app_service_plan`, `azurerm_app_service`
- **Steps**:
    1. Create an App Service plan.
    2. Deploy a web app within the App Service plan.

### Challenge 6: Configure Azure SQL Database
- **Objective**: Set up an Azure SQL Database.
- **Resources**: `azurerm_sql_server`, `azurerm_sql_database`
- **Steps**:
    1. Define the SQL server resource.
    2. Create a SQL database within the server.

### Challenge 7: Deploy Azure Kubernetes Service (AKS)
- **Objective**: Provision an AKS cluster.
- **Resources**: `azurerm_kubernetes_cluster`
- **Steps**:
    1. Define the AKS cluster resource.
    2. Configure node pools and networking.

### Challenge 8: Set Up Azure DNS Zone
- **Objective**: Create a DNS zone and add records.
- **Resources**: `azurerm_dns_zone`, `azurerm_dns_a_record`
- **Steps**:
    1. Define the DNS zone resource.
    2. Add A records to the DNS zone.

### Challenge 9: Implement Azure Load Balancer
- **Objective**: Configure a load balancer with backend pools.
- **Resources**: `azurerm_lb`, `azurerm_lb_backend_address_pool`
- **Steps**:
    1. Define the load balancer resource.
    2. Configure backend address pools and rules.

### Challenge 10: Set Up Azure Function App
- **Objective**: Deploy a serverless function app.
- **Resources**: `azurerm_function_app`, `azurerm_storage_account`
- **Steps**:
    1. Create a storage account.
    2. Define the function app resource.

# Resources 
- [Terraform Azure Provider Documentation](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)
- [Azure Terraform Samples](https://github.com/Azure/terraform)
- [Terraform Azure Modules](https://registry.terraform.io/namespaces/Azure)
- [Azure Terraform Best Practices](https://docs.microsoft.com/en-us/azure/developer/terraform/best-practices)
- [Terraform AzureRM Provider GitHub](https://github.com/hashicorp/terraform-provider-azurerm)