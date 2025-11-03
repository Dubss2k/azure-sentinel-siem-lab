<div align="center">
  
# Azure Sentinel Security Monitoring

</div>

## ☁️ Project Description
- Configured a Microsoft Sentinel SIEM environment in Azure to collect and analyze security events from a Windows VM honeypot.
- Security logs were collected via a Log Analytics Workspace, analyzed using KQL, and visualized through an interactive attack map showing global login attempts.
- This project served as a practical exercise in understanding how cloud-based log collection and analysis can support threat monitoring.

## 🛠️ Tools Used
  - Microsoft Azure Cloud Computing
  - Microsoft Sentinel
  - Log Analytics Workspace
  - Azure Virtual Machine Honeypot (Windows)
  - KQL (Kusto Query Language)
  - Microsoft Defender for Cloud
    
## 🧠 Key Features
  - Detecting failed login attempts using KQL queries.
  - Identified attacker IPs.
  - Visualized attack data on a global map through IP locations in Microsoft Sentinel.

## 🌐 Project Showcase

<div align="center">
  
### Image displays high level overview of start to finish proccess flow:

</div>

 ![](images/Azure_Sentinel_SIEM_Overview.png)
 
## 🏗️ Resource Group Infrastructure
<div align="center">
  
 ### Showing the underlying objects that are needed to complete this project :
 
</div>

  ![](images/Azure_Structure.png)
  
<div align="center">
  
 ### KQL Query Showcasing # of Attacks Per IP Address:
 
</div>

  ![](images/Sample_KQL_Query.png)

  ## 🌍 Attack Map Visualization
  
<div align="center">
    
  ### This is the final mapping of IP Adresses tied to geolocation:
</div>

  ![](images/VM_AttackMap.png)
  
## 🎓 Learning Outcomes
- Gained hands-on experience setting up and configuring Microsoft Sentinel.
- Learned how to collect and analyze security events from an Azure VM.
- Improved understanding of log analytics and basic SIEM query development.
