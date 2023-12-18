<h1>Implementing a Honeynet in Azure </h1>

<h2>Description</h2>
This lab aim to illustrate the integration of Azure Sentinel, a cloud-native Security Information and Event Management (SIEM) solution, with a virtual machine (VM) on Microsoft Azure. Specifically, the focus is on examining unsuccessful Remote Desktop Protocol (RDP) logs using PowerShell to extract IP addresses from the Windows Event Viewer. This data is then transmitted to a third-party API, which determines the latitude, longitude, state, and country associated with the IPs. The results are sent back to the virtual machine, generating a custom log with geographic data. Subsequently, the log file is directed to Azure Sentinel for centralized monitoring and analysis, facilitating the creation of a world map highlighting the origins of brute force attacks
<br />



<h2>Languages and Utilities Used</h2>

- <b>Powershell</b>
- <b>Kusto Query Language (KQL)</b>

<h2>Environments Used </h2>

- <b>Azure Environment</b> 
  - <b>Virtual Machine</b>
  - <b>Log Analytics</b>
  - <b>Sentinel</b>
- <b>Windows 10 IS0</b>
- <b>IPgeolocatio.io (3rd party API)</b>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
