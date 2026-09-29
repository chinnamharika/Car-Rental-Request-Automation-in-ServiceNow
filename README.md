# Car-Rental-Request-Automation-in-ServiceNow
project Overview:

This project automates the end-to-end **Car Rental Request** process within ServiceNow. By replacing traditional manual email and paper-based requests with a digital Service Catalog item, the system streamlines request submissions, automated manager approval routing, fulfillment task assignments for fleet teams, and exception management.

Key Features & Implementation Phases:

Phase 1: Requirement Analysis & Planning

Configured the user-facing Car Rental Request Catalog Item under the Transportation Services category in the Service Portal (/sp).

Designed 7 core form variables (requestor, requested_date, pickup_location, drop_location, duration_hrs, car_type, and reason).

Phase 2: Backend Development & Configurations Data Architecture

Built dynamic request routing using Flow Designer.

Structured table associations across sc_req_item (RITM) and sc_task (SCTASK).

Configured backend Business Rules to handle exceptions (e.g., auto-creating an Incident when a car is unavailable).

Phase 3: UI/UX Development & Customization

Formatted the Service Portal interface (/sp) for seamless user experience.

Enabled field validations, mandatory input enforcement, and order confirmation tracking.

Phase 4: Data Migration, Testing & Security

Executed end-to-end testing of request submissions, approval states, and task fulfillment workflows.

Applied User Criteria and Role-Based Access Control (RBAC) to secure request data.

Phase 5: Deployment, Documentation & Final Presentation

Packaged all configurations into a single ServiceNow Update Set.

Exported system configuration backup (Car_Rental_Request_Setup.xml).

Installation & Setup Guide

To import and deploy this project into your ServiceNow Instance:

Download Update Set: Clone this repository or download Car_Rental_Request_Setup.xml.

Retrieve Remote Update Set:

Log in to your ServiceNow Instance as System Administrator.

Navigate to System Update Sets > Retrieved Update Sets.

Click Import Update Set from XML and select Car_Rental_Request_Setup.xml.

Commit Update Set:

Open the imported record (Car Rental Request Setup).

Click Preview Update Set to verify no errors.

Click Commit Update Set to apply all configurations.

Verification:

Navigate to Service Portal (/sp) > Service Catalog.

Search for Car Rental Request and test the submission lifecycle.
