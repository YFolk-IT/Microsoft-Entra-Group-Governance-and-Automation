Project Overview
In this lab, I managed the creation and configuration of different group types within Microsoft Entra ID. I implemented both static and dynamic membership rules, demonstrating how to automate security access and resource allocation (licenses) for specific user populations.
•	Tools Used: Microsoft Entra Admin Center, Microsoft 365 Admin Center.
•	Key Focus: Resource Governance, Dynamic Query Logic, and Role Delegation.
Technical Execution
1. Microsoft 365 Group Collaboration
•	Task: Provisioned a collaboration-focused group (Project23).
•	Process: Configured a Microsoft 365 group with a specific business use case (AI Simulation Project) and oversaw the manual assignment of core project members.
2. Automated Security via Dynamic Membership
•	Task: Scaled security management using Dynamic Groups.
•	Process: Executed the creation of a "Guest Users" security group. I implemented a Dynamic User Query using the logic (user.userType -eq "Guest") to ensure any current or future guests are automatically added to this security perimeter without manual intervention.
3. Membership Life-Cycle Management
•	Task: Updated group memberships using multiple administrative pathways.
•	Process: Demonstrated technical flexibility by adding users to groups via both the Groups Interface and the User Profile Interface, ensuring all project contributors (including external guests) were correctly associated with relevant resources.
4. Group Governance: Owners & Licensing
•	Task: Delegated administrative authority and managed resource costs.
•	Implementation:
o	Ownership Delegation: Assigned Bhogeswar Kalita as a Group Owner to facilitate decentralized management.
o	Group-Based Licensing: Utilized the Microsoft 365 Admin Center to assign Power Automate Free licenses to the entire group, ensuring all members receive necessary software seats automatically.

Security Analysis & Best Practices
•	Dynamic Groups vs. Manual Errors: By utilizing Dynamic Membership for guests, I reduced the risk of "stale" permissions. Users are added or removed based on their actual attributes, which is a key component of Identity Governance.
•	Delegated Administration: Assigning group owners follows the Principle of Least Privilege. By allowing project leads to manage their own members, we reduce the need for high-level Global Admin intervention for routine tasks.
•	License Optimization: Implementing Group-Based Licensing ensures that licenses are only consumed by active members of a specific project, preventing "license sprawl" and reducing company costs.

Evidence of Completion
> [!NOTE]
> All sensitive Tenant IDs and Admin accounts have been redacted to maintain Operational Security.

### Automated Membership: Dynamic Query Configuration
![Dynamic Query](./01-dynamic-query.png)

### Administrative Delegation: Group Ownership
![Group Owners](./02-group-owners.png)

### Resource Allocation: Group-Based Licensing
![Group Licensing](./03-group-license.png)

Learning Credits
This lab is based on the Microsoft Learn module: Perform basic Group Management tasks in Microsoft Entra ID.
