# IGA-SoftAppliance

This is a software appliance that can run an Identity Governance and Administration (IGA) platform. This can be used for small deployments in a production environment (under 250 identities) or used as an isolated development/lab environment.

This project includes a soft appliance based on a LAMP stack, using CentOS 7. The soft appliance is distributed as an Open Virtual Appliance (OVA) image. This will contain everything needed to build out a development/learning environment, including the open source OrangeHRM application to serve as the authoritative source of truth for identities. If using in a production environment some additional configurations will be required based on the business needs and existing infrastructure.

This software appliance DOES NOT contain any IGA software pre-installed. The soft appliance is designed to run IGA platforms such as SailPoint IIQ, RSA IGL, One Identity: Identity Manager, or Core Security- Access, Provisioning, & Identity Suite; as examples. The previously mentioned examples do require licensing, please reach out to those vendors if needed. You can also use free and/or open source platforms such as OpenIAM (__www.openiam.com__) or Soffid (__www.soffid.com/__).

## Deployment

#### _Enterprise_
Within an enterprise environment, using bare metal, it is recommended to use ESXi/vSphere, Xen, or Proxmox. If Hyper-V is preferred, then you will need to leverage a 3rd tool to convert the OVA to a VHD format. Using Hyper-V is not recommended or supported at the moment. You can also also leverage the AWS CLI to deploy the OVA to an EC2 instance. Navigate here for guidance: __https://aws.amazon.com/ec2/vm-import/__

#### _Lab Environment_
If used as an isolated learning/lab environment VirtualBox or VMware Workstation Player should be used. VirtualBox is preferred and recommended.

#### _Default Usernames/Passwords_
All default usernames and passwords are included within the Description of the OVA image itself. It is also available in the _ReadMe.txt_ file on the desktop. All passwords should be changed immediately if this is being deployed within an enterprise. It is also recommended to changed default usernames/passwords even if only being used locally or within a lab environment.

#### _Default VM Configs_
The default settings for the soft appliance are as follows; change accordingly as needed
- vCPU: 2
- RAM: 4GB
- Storage: 50GB (Dynamically Allocated)
- NIC: Bridged Adapter
- Shared Clipboard: Bidirectional

## Stack
- CentOS 7 <br />
- Apache 2.4 <br />
- Tomcat 8.0 <br />
- MariaDB 5.5 <br />
- PHP 5.6 <br />
- Postfix/Cyrus <br />

## Software
- OrangeHRM
- OpenLDAP
- Apache Directory Studio
- Thunderbird
- DBeaver
- phpMyAdmin
- phpLDAPadmin
- Sublime 3

## Download OVA
__https://ad3.in/IGA_SoftAppliance__ <br />

version: 1.0.1 <br />
MD5: 084124fdc6412621e24a56dae5090f2a <br />
SHA1: c6155fa1998783efe627248e151ba79fd68a78df <br />

## Disclaimer
This software appliance is provided “as is,” with all faults, and Abrom Douglas III express no representations or warranties, of any kind related to this software appliance or the materials contained within this GitHub Repo. Also, nothing contained within this software appliance shall be interpreted as advising you. 

In no event shall Abrom Douglas III be held liable for anything arising out of or in any way connected with your use of this software appliance.

The IGA_SoftAppliance is 100% free of charge as all software contained within is free and/or open source (including Apache, GPL, MIT, Eclipse, or Creative Commons).
