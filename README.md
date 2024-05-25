# Class work from May 24 2024

**Data Source: azurerm_resource_group**

Link: https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/data-sources/resource_group

Description: Use this data source to access information about an existing Resource Group.

To create a resource group on Azure:
<img width="978" alt="image" src="https://github.com/njlatonio/mcitazurerm-loadbalancer/assets/168039404/125b4f1c-c9c6-4b91-b30a-ec39f768ab09">

Make sure you enter:
- name
- location


**Data Source: azurerm_subnet**

Link: https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/data-sources/subnet

Description: Use this data source to access information about an existing Subnet within a Virtual Network.

To create a new subnet on Azure:
![image](https://github.com/njlatonio/mcitazurerm-loadbalancer/assets/168039404/496a3cc6-44d7-45c7-a25c-7f03c94a87d7)
![image](https://github.com/njlatonio/mcitazurerm-loadbalancer/assets/168039404/543d708e-4d9a-4088-8dab-14cefde20709)
![image](https://github.com/njlatonio/mcitazurerm-loadbalancer/assets/168039404/c4167e0e-74ff-41cf-98b3-7b652dc4383e)


**resource "azurerm_public_ip"**

Link: https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/public_ip

Description: Manages a Public IP Address.

To create a public IP address on Azure:
![image](https://github.com/njlatonio/mcitazurerm-loadbalancer/assets/168039404/1335b459-666d-4ff9-a9f0-be1c242914ed)
![image](https://github.com/njlatonio/mcitazurerm-loadbalancer/assets/168039404/ec796302-8d0c-4715-8f3f-d10c95231383)
![image](https://github.com/njlatonio/mcitazurerm-loadbalancer/assets/168039404/047fed53-d915-4ae1-b419-1fa1d3e7b9a5)

Make sure to complete all fields with a red *

**resource "azurerm_lb"**

Link: https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/lb

Description: Manages a Load Balancer Resource.

To create a load balancer on Azure:
<img width="980" alt="image" src="https://github.com/njlatonio/mcitazurerm-loadbalancer/assets/168039404/f98bfc7a-3312-400c-a8a8-50980d44e351">

Make sure you enter:
- resource group name
- name
- location
- SKU (Standard/Gateway/Basic)
- Type (Public/Internal)
- Tier (Regional/Global)


**resource "azurerm_lb_backend_address_pool"**

Link: https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/lb_backend_address_pool_address

Description: Manages a Backend Address within a Backend Address Pool.


**resource "azurerm_lb_nat_rule"**

Link: https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/lb_nat_rule.html

Description: Manages a Load Balancer NAT Rule.


**resource "azurerm_lb_probe"**

Link: https://registry.terraform.io/providers/hashicorp/azurerm/2.99.0/docs/resources/lb_probe

Description: Manages a LoadBalancer Probe Resource.


**resource "azurerm_lb_rule"**

Link: https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/lb_rule.html

Description: Manages a Load Balancer Rule.

