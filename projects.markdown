---
layout: page
title: Projects
permalink: /projects/
---
![Bifrost](/assets/BifrostLogo.png)

![OE-COLS](/assets/swisscom-logo-small.png)

_OECOLS_ is the WARP network ordering engine. It orchestrates the ordering of WARP networks
for big customer. OECOLS is responsible of receiving the orders, creating the physical entities,
delegating work to other Swisscom systems, up to the electrician that connects the routers.

![ERIS](/assets/swisscom-logo-small.png)

_ERIS_ is responsible for in-house installation order tracking with optimized usability and reporting capabilities for CFU's Tools.
It should support the electrician installation task. It will not be a substitute for general order tracking with Fit4SIP. But It must be able to integrate the applications used by ESIP and automate the OE-COLS provisioning process.
_ERIS_ gives the possibility to the CFUs to have the view on the orders that concern them. And eventually let them intervene in the installation process.
Comissioning the installer (electrician) via the media in use by CFUs
Planning and confirmation of the in-house installation appointment
Tracking and postponing the in-house installation appointment
Recording the completion message of the installation


![OrderMonitor](/assets/swisscom-logo-small.png)

_ORDERMONITOR_ is responsible for keeping track of all WARP orders. Allowing the
user to understand in which state the oder is. If there is any issue, the system
will point in which subsystem the issue is.

![DataBroker](/assets/swisscom-logo-small.png)

_DATABROKER_ is a microservice for high availability of _OECOLS_ data access.