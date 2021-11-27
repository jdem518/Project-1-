# Project-1-
These files have been tested and used to generate a live ELK deployment on Azure. They can be used to either recreate the entire deployment pictured above. Alternatively, select portions of the YAML files may be used to install only certain pieces of it, such as Filebeat.

This document contains the following details:

Description of the Topology
Access Policies
ELK Configuration
Beats in Use
Machines Being Monitored
How to Use the Ansible Build
Description of the Topology
The main purpose of this network is to expose a load-balanced and monitored instance of DVWA, the D*mn Vulnerable Web Application.

Load balancing ensures that the application will be highly protected, in addition to restricting traffic to the network.

Integrating an ELK server allows users to easily monitor the vulnerable VMs for changes to the logs and system metrics.

The configuration details of each machine may be found below.

Name	|Function|	IP Address|	Operating System
Jump Box|	Gateway|	10.0.0.4|	Linux Ubuntu 18.04
Web-1	Dvwa|	10.0.0.5|	Linux Ubuntu 18.04
Web-2	Dvwa |	10.0.0.6|	Linux Ubuntu 18.04
ELK-VM|	Kibana|	10.1.0.4|	Linux Ubuntu 18.04
