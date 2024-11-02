# osTicket Help Desk System Configuration

This document outlines key post-install configurations performed on the osTicket help desk system, demonstrating skills in system setup, permissions management, and ticketing configuration.

## Key Access URLs
- **Admin/Analyst Login**: [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End User Access**: [http://localhost/osTicket](http://localhost/osTicket)

## Essential Configuration Steps

### Roles and Permissions
- **Roles**: Created "Supreme Admin" role to manage high-level agent permissions.
- **Departments**: Configured departments for ticket visibility, including **SysAdmins**, **Help Desk**, and **Networking**.

### Team Setup
- **Teams**: Created a cross-department team (e.g., **Online Banking**) to enable specialized support grouping.

### Ticket Access Settings
- **User Permissions**: Configured system to allow unregistered users to submit tickets, ensuring accessibility for end-users.

### Agent and User Management
- **Agents**: Added support staff with assigned departments (e.g., SysAdmins and Support).
- **End Users**: Created user profiles to simulate customer interactions with the ticketing system.

### Service Level Agreements (SLA)
- **SLAs Configured**:
  - **Sev-A**: 1-hour response time, 24/7 coverage.
  - **Sev-B**: 4-hour response time, 24/7 coverage.
  - **Sev-C**: 8-hour response time, business hours only.

### Help Topics
- **Categories Created**: Set up ticket categories like **Business Critical Outage**, **Password Reset**, and **Equipment Request** to streamline user requests.

