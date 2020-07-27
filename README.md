<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# CTX-Azure
Cortex Subtasks which interact with Microsoft Azure without using the Microsoft Azure Graphical User Interface.

The module allows users to perform the following functionality:
* Resource Group
	* Create Resource Group
* Networking
	* Create Network Interface
	* Create Public IP
	* Create Subnet
	* Create Virtual Network
* Virtual Machines
	* Create VM From Template
	* Deallocate VM
	* Delete VM
	* Get VM Details
	* Get VM Name and Resource Group
	* Get VM Status
	* Restart VM
	* Start VM
*  Availability Sets
	* Deallocate Availability Set VMs
	* Get Availability Set VMs
	* Start Availability Set VMs
* User Management
	* Get User Membership
	* Get Users

## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other-requisites)
1) [Support and Warranty](#support-and-warranty)
1) [Installation](#installation)
1) [How to use](#how-to-use)
1) [How you can contribute](#how-you-can-contribute)
1) [Versioning](#versioning)
1) [Licensing](#licensing)

## Dependencies
### Cortex Version
This version of the CTX-Azure module was developed in Cortex v6.3.0. Some functionality may not be available in earlier verions of Cortex.

### OCIs
None Required.

### Files
The CTX-Azure module requires the following files:
* [CTX-Azure Studio Package](https://github.com/CortexIntelligentAutomation/CTX-Azure/releases/download/v1.0/CTX-Azure.studiopkg)

### Other Requisites
The CTX-Azure module requires an 'Azure Active Directory Application' to be created. Details on how to create this can be found in the [User Guide](https://github.com/CortexIntelligentAutomation/CTX-Azure/blob/master/CTX-Azure%20-%20User%20Guide.pdf).

## Support and Warranty 
This module is supplied as a template that you can amend and extend to fit your requirements, as such it is not supported as part of the Cortex Product suite under the Cortex product support agreement.

## Installation
Details of how the module should be imported into Cortex can be found in the [Deployment Plan](https://github.com/CortexIntelligentAutomation/CTX-Azure/blob/master/CTX-Azure%20-%20Deployment%20Plan.pdf).

## How to use
A detailed User Guide has been provided with instructions on how to use the flows/subtasks, available [here](https://github.com/CortexIntelligentAutomation/CTX-Azure/blob/master/CTX-Azure%20-%20User%20Guide.pdf). Configuration of subtask inputs and outputs are detailed in notes on the subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
The CTX-Azure module has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.0 | 10/10/2018 | Create VMs | Created
v1.0 | 10/10/2018 | Deallocate VMs | Created
v1.0 | 10/10/2018 | Delete VMs | Created
v1.0 | 10/10/2018 | Start VMs | Created
v1.0 | 10/10/2018 | Restart VMs | Created
v1.0 | 10/10/2018 | Create Resource Group | Created
v1.0 | 10/10/2018 | Create Network Interface | Created
v1.0 | 10/10/2018 | Create Public IP | Created
v1.0 | 10/10/2018 | Create Subnet | Created
v1.0 | 10/10/2018 | Create Virtural Network | Created
v1.0 | 10/10/2018 | Get User Membership | Created
v1.0 | 10/10/2018 | Get Users | Created
v1.0 | 10/10/2018 | Get VM Status | Created
v1.0 | 10/10/2018 | Get VM Details | Created
v1.0 | 10/10/2018 | Get VM Name and Resource Group | Created
v1.0 | 10/10/2018 | Start Availability Set VMs | Created
v1.0 | 10/10/2018 | Get Availability Set VMs | Created
v1.0 | 10/10/2018 | Deallocate Availability Set VMs | Created
v1.0 | 10/10/2018 | Get Authentication Token | Created
v1.0 | 10/10/2018 | HTTP Error Handling | Created

## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2018 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
