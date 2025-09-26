🚀 Streamlined Ticket Assignment System for ServiceNow
📖 Overview
This project is a student-built solution to automate support ticket routing in ServiceNow using Flow Designer. It assigns tickets to the right support groups based on roles, categories, and issue types, reducing manual work, speeding up resolutions, and improving user experience.

🎯 Objectives
Automate ticket assignment to save time.
Reduce manual effort for support teams.
Speed up response and resolution for users.
Create a flexible system for future growth.

🏗️ Project Setup & Progress
Day 1 – Getting Started

Set up Users for platform and certification issues.
Created Groups: Platform Group and Certification Group.
Defined Roles: platform_role and certification_role, linked to groups.
Built a Custom Table: u_operations_related for ticket tracking.
Added Choice Fields for issue types (e.g., login errors, 404 errors, certificates).
Configured Application Access and ACLs (Read, Write, Delete, Create) for security.

Day 2 – Building Automation

Created Flow Designer Flows:
Flow 1 – Certificates: Sends certificate-related tickets to the Certification Group.
Flow 2 – Platform: Routes platform issues (e.g., login problems, 404 errors) to the Platform Group.


Tested flows with sample tickets and checked Flow Designer Execution Logs to ensure they worked.

🗂️ Table Structure
The u_operations_related table is designed for ticket management:

Field Name
Type/Description

Assigned to Group
Reference to Group

Assigned to User
Reference to User

Service Request No
Auto/Manual Ticket ID

Name
Short description/title

Ticket Raised Date
Date/Time of ticket creation

Priority
Choice (High/Medium/Low)

Issue
Choice (Login Error, 404, Certificates, User Expired)

Comment
Additional notes

Created By / Updated By
Audit info

🚀 Next Steps

Add email/SMS notifications to alert assigned groups.
Build dashboards to track ticket resolution times.
Add more conditions and groups for future needs.

🖼️ Screenshots
Screenshots are in the assets folder:

CreateTable.png – Table fields.
CreatedAcls.png – ACL setup.
Flow1_Certificate.png – Certificate flow in Flow Designer.
Flow2_Platform.png – Platform flow in Flow Designer.
ExecutionLogs.png – Flow execution logs.

🛠️ Tools Used

ServiceNow: For table setup, roles, ACLs, and automation.
Flow Designer: For creating automated workflows.


📜 License
This is a student project for learning purposes. Feel free to modify it based on your organization’s ServiceNow policies.

🌟 Why This Project Matters
As a student, I built this to learn ServiceNow and automation. It shows how to streamline ticket routing, save time, and improve support processes. It’s a fun and practical way to explore Flow Designer and ServiceNow’s power!
