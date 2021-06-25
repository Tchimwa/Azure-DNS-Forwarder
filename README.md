# Azure-DNS-Forwarder

This template will deploy a server level DNS forwarder on Windows server with 168.63.129.16 on Azure. 
A server level DNS forwarder is very helpful with some DNS scenarios whren it comes to Azure Private Endpoint.
You will need you DNS forwarder to access the Private Zone created by the Azure Private Endpoint and managed by 168.63.129.16

#Specific cases

Below are the specific cases where you need a DNS forwarder on Azure:
- Using custom DNS with no DNS servers on Azure
- Trying to access your PaaS resources using the Azure Private via VPN ( Point-to-Site, Site-to-Site, ExR)

