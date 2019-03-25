# Create Virtual Machines under a Load balancer and configures Load Balancing rules for the VMs


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fesatemre%2Fazure-template%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fesatemre%2Fazure-template%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template allows you to create 2 Virtual Machines under a Load balancer and configure a load balancing rule on Port 80. This template also deploys a Storage Account (Gen2 Enabled), Key Vault, Virtual Network, Public IP address, Availability Set and Network Interfaces.

In this template, we use the resource loops capability to create the network interfaces and virtual machines



[25-03-2019 12:00] Research about azure quickstart templates to find convenient starter template for our case.

[25-03-2019 13:30] Create the template based on an azure quickstart template (201-2-vms-loadbalancer-lbrules)

[25-03-2019 15:30] All desired resources were added to the template.

[25-03-2019 16:00] All minor bugs are fixed.

[25-03-2019 16:30] The template is uploaded to Github.
