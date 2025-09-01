Time Off Request Application
📖 Overview

The Time Off Request Application is a custom ServiceNow application designed to streamline the process of requesting, approving, and managing employee leave. It eliminates manual paperwork by providing a simple and automated workflow for both employees and managers.

🎯 Key Features

Request Submission – Employees can submit leave requests with details like leave type, start date, end date, and reason.

Approval Workflow – Requests are automatically routed to the assigned approver (e.g., manager such as Fred Luddy in the demo).

Notifications – Email/ServiceNow notifications alert employees and managers when a request is submitted, approved, or rejected.

Leave Tracking – Employees can view the status of their requests (Pending, Approved, Rejected).

Admin Control – HR/Admin can configure leave policies, track employee leaves, and maintain records.

⚙️ Technical Implementation

Platform: ServiceNow (Built using App Engine Studio)

Data Model:

Time Off Request table (custom table)

Fields: Employee Name, Request Type, Start Date, End Date, Status, Approver, Comments

Process Flow: Designed using Flow Designer for automated request approvals.

UI: Form layout for employees to submit requests + List view for managers/admins.

Scope: Scoped application to ensure modularity and reusability.

📊 Benefits

✅ Reduces manual approval delays

✅ Transparent leave tracking for employees

✅ Centralized system for HR

✅ Can be extended to integrate with calendars and payroll
