# IGA-SoftAppliance
Creator: Abrom Douglas III <br />
Project Name: IGA SoftAppliance

------------------------------------------------
This is a software appliance that can run an Identity Governance and Administration (IGA) platform. This can be used for small deployments in a production environment or used as an isolated development environment.

This project includes a soft appliance based on a LAMP stack, using CentOS 7 as the OS. The soft appliance is distributed as an Open Virtual Appliance (OVA) image. This will contain everything needed to build out a development/learning environment, including the open source OrangeHRM to be to authoritative source of truth for identities.

This soft appliance DOES NOT contain any IGA software. This stack is designed to run IGA platforms such as SailPoint IIQ, RSA IGL, One Identity- Identity Manager, OpenIAM, Soffid, or Core Security- Access, Provisioning, & Identity Suite.

Note: The default username and password for this soft appliance happens to be sailpoint. However, this is not associated to SailPoint Technologies at all. This can/should be changed upon initial configuration.

------------------------------------------------

### Stack
- CentOS 7 <br />
- Apache 2.4 <br />
- Tomcat 8.0 <br />
- MariaDB 5.5 <br />
- PHP 5.6 <br />
- Postfix/Cyrus <br />

### Software
- OrangeHRM
- OpenLDAP
- Apache Directory Studio
- Thunderbird
- DBeaver
- phpMyAdmin
- phpLDAPadmin
- Sublime 3
