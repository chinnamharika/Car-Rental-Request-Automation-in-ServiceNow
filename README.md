# Car-Rental-Request-Automation-in-ServiceNow

 A ServiceNow-based automation project that streamlines the complete car rental request lifecycle — from Service Catalog submission and manager approval to fleet fulfillment and request closure.


## Project Overview

The **Car Rental Request Automation** project is developed using **ServiceNow** to automate the process of requesting and managing company car rentals.

Employees can submit a car rental request through the **Service Portal**. The request is automatically processed through approval and fulfillment stages using **Flow Designer, Service Catalog, Business Rules, and ServiceNow task management**.

The project demonstrates an end-to-end ServiceNow workflow with proper request tracking, automation, testing, and deployment using Update Sets.



## Project Objectives

- Create a centralized Car Rental Request process.
- Allow employees to submit requests through the Service Portal.
- Automate manager approval.
- Automatically generate fulfillment tasks for the Transport/Fleet team.
- Track requests using REQ, RITM, and SCTASK.
- Implement backend automation using Business Rules.
- Automate the request lifecycle using Flow Designer.
- Package configurations using Update Sets.
- Provide a structured and traceable request management process.



## ServiceNow Technologies & Features

| Technology / Feature | Usage |
|---|---|
| **Service Catalog** | Car Rental Request submission |
| **Service Portal** | User-facing request interface |
| **Flow Designer** | Approval and fulfillment automation |
| **Business Rules** | Backend automation and logic |
| **Catalog Variables** | Capture request information |
| **Approvals** | Manager approval process |
| **REQ / RITM / SCTASK** | Request lifecycle tracking |
| **Update Sets** | Configuration packaging and deployment |
| **ServiceNow PDI** | Development and testing environment |



## End-to-End Workflow

```text
Employee
   │
   ▼
Service Portal
   │
   ▼
Car Rental Request
   │
   ▼
REQ / RITM Created
   │
   ▼
Manager Approval
   │
   ├──────────────► Rejected
   │                    │
   │                    ▼
   │               Request Closed
   │
   ▼
Approved
   │
   ▼
Fleet / Transport Fulfillment Task
   │
   ▼
Car Assignment & Fulfillment
   │
   ▼
Request Closure

```



## Documentation

Detailed project documentation covering all five implementation phases is available in the `Documentation` folder.

[View Project Documentation](https://drive.google.com/drive/folders/1IaNIrD4T2IE_VfY-SsXToHQwCjs7A5nt?usp=sharing)



## Demo Video

The complete project workflow and ServiceNow implementation are demonstrated in the project demo video.

[Watch Demo Video](https://drive.google.com/file/d/19_i9aydVxuRa3UDV-7zh9j7bwbwAyyPd/view?usp=drive_link)



