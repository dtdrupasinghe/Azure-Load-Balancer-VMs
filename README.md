Introduction
As part of my continuous learning in cloud computing, I recently completed a practical project on Microsoft Azure where I deployed a high-availability web infrastructure using two Virtual Machines (VMs) and a Load Balancer. This hands-on experience helped me understand how traffic can be automatically distributed and redirected to ensure uninterrupted service.

Project Overview
🔹 Objective: To build a fault-tolerant web setup using Azure free-tier services by:

* Deploying 2 Linux-based virtual machines
* Installing Apache2 web servers with individual messages
* Distributing traffic via a public load balancer
* Monitoring traffic flow and availability using Azure Monitor

🔹 Technologies Used:

* Azure Virtual Machines (Ubuntu 22.04 LTS)
* Azure Basic Load Balancer
* Azure Monitor & Log Analytics
* Apache Web Server

Implementation Steps
✅ Created Resource Group: Grouped all resources for better management and cost tracking.
✅ Deployed Two Virtual Machines:

* Installed Apache2
* Configured custom web pages: “Hello from VM1” & “Hello from VM2”

✅ Configured Load Balancer:

* Setup health probe on port 80
* Added both VMs to backend pool
* Created load balancing rule to distribute web traffic

✅ Monitored Traffic:

* Used Azure Monitor to check logs and VM health
* Verified that stopping one VM redirected traffic to the other automatically

Insights Gained

* Working with virtual networks and compute resources.
* Configuring and testing load balancer behavior 
* Installing and managing web servers on Linux.
* Monitoring traffic patterns using Azure Monitor.s
* Troubleshooting permissions and SSH access issuezs

Join with me :

LinkedIn : www.linkedin.com/in/thisararupasinghe
Youtube : https://youtube.com/@thisararupsinghe?si=c7IqC1F1-LfiO454
