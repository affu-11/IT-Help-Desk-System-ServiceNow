 IT Help Desk Ticketing System – ServiceNow

## Project Overview
Developed a custom IT Help Desk Ticketing System using ServiceNow to manage and track IT support tickets efficiently.

##  Features
- Ticket creation and management
- Incident status tracking
- Category and priority management
- Business Rule automation
- UI Policy implementation
- Reports and dashboards

## Technologies Used
- ServiceNow
- ITSM
- Business Rules
- UI Policies
- Table & Form Configuration

## Business Rule Automation
Implemented a Business Rule to automatically assign tickets when Priority is set to High.

## UI Policy
Configured UI Policies to dynamically manage form behavior based on ticket status.

## Project Screenshots

### Application Dashboard
<img width="1918" height="966" alt="application_dashboard png" src="https://github.com/user-attachments/assets/fde6eebe-de03-44e7-a330-d75bcc7132a5" />

This screenshot shows the main configuration page of the custom **IT Help Desk System** application created in ServiceNow. The dashboard includes application scope settings, runtime configuration, JavaScript mode setup, subscription management, and studio access permissions used for managing the overall application environment.


### Ticket Records

<img width="1912" height="968" alt="ticket_records png" src="https://github.com/user-attachments/assets/4e361f91-cb2e-4de6-ae8c-841b829d9252" />

The Ticket Records screenshot displays multiple sample IT support tickets created within the application. Each ticket contains important details such as ticket number, category, priority, status, and assigned user. Categories include Hardware, Software, Network, and Access-related incidents. The records demonstrate how the system can efficiently track and manage support requests while maintaining organized incident data similar to real-world ITSM environments.

### Business Rule
<img width="1913" height="972" alt="Business rule1 png" src="https://github.com/user-attachments/assets/e7ccdb53-91d1-45f8-983e-254b8c84ee0f" />

This screenshot shows the detailed configuration of the **Auto Assign High Priority** Business Rule created in the ServiceNow IT Help Desk System. The rule is associated with the Ticket table and is configured to execute before Insert and Update operations. This setup helps automate ticket handling processes and improves the efficiency of incident management within the system.


<img width="1878" height="889" alt="Business rule2 png (2)" src="https://github.com/user-attachments/assets/77854bb0-19e0-45e2-bedd-efa7eaba2d1a" />

This screenshot displays the server-side scripting logic implemented inside the Business Rule. The script uses `gs.getUserID()` to automatically assign the currently logged-in user to the ticket whenever the rule conditions are satisfied. This automation reduces manual assignment effort and ensures faster handling of high-priority incidents.

 
<img width="1914" height="935" alt="Business rule3 png" src="https://github.com/user-attachments/assets/ced94d12-4123-4a82-8af3-52fb19ad3263" />

This screenshot shows the filter conditions configured for the Business Rule. The rule is triggered only when the ticket priority is set to **High**. By applying conditional automation, the system ensures that urgent tickets are identified quickly and assigned automatically for immediate action and faster issue resolution.


### UI Policy
<img width="1913" height="956" alt="UI Policy1 png" src="https://github.com/user-attachments/assets/335af4a3-eda0-4755-ac7a-56ec523f8667" />

This screenshot shows the configuration of the **Make Description Mandatory** UI Policy created in the ServiceNow IT Help Desk System. The policy is applied to the Ticket table and is configured to trigger when the ticket status changes to **Resolved**. This ensures that users provide proper issue resolution details before closing or resolving a ticket, improving data accuracy and documentation quality within the help desk process.

<img width="1903" height="966" alt="UI Policy2 png" src="https://github.com/user-attachments/assets/3de8567a-cb7e-41c8-acea-fba921419dca" />


This screenshot displays the UI Policy Actions configured for the **Make Description Mandatory** policy. The description field is set as mandatory whenever the defined conditions are met. The policy also uses reverse conditions to automatically remove the mandatory requirement when the ticket status changes back from Resolved, creating a dynamic and user-friendly form behavior.


### Reports Dashboard

Created interactive reports and dashboards in ServiceNow to visualize ticket data and monitor help desk performance effectively. The reports provide insights into ticket status distribution and priority-wise incident tracking.

<img width="1909" height="961" alt="Screenshot 2026-05-08 154702" src="https://github.com/user-attachments/assets/226c5dcd-2659-404c-a085-536eecaa2a23" />

Designed a bar chart report to display ticket records based on their current status, such as Open and Resolved. This report helps track the progress of incidents and provides visibility into how many tickets are still pending versus successfully completed.

1. Displays real-time ticket status distribution
2. Helps monitor pending and resolved incidents
3. Improves incident tracking and workflow visibility
4. Supports faster analysis of support team performance
<img width="1913" height="976" alt="Screenshot 2026-05-08 154827" src="https://github.com/user-attachments/assets/b2a3e84c-d01a-4c3e-8705-ef7247a1fbde" />
<img width="1912" height="961" alt="Screenshot 2026-05-08 154927" src="https://github.com/user-attachments/assets/0703b25d-1d78-4b30-ac97-7081d8cd0444" />




##  Outcome
Successfully developed a beginner-level IT Help Desk workflow system similar to real-world incident management applications used in organizations.# IT-Help-Desk-System-ServiceNow
Custom IT Help Desk Ticketing System developed using ServiceNow with Business Rules, UI Policies, ticket management, and reporting features.
