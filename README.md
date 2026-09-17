# Identity Lifecycle Management in Microsoft Azure's Entra ID

## Objective

Manage a user account through the full identity lifecycle: joiner, mover, and leaver, in Microsoft Entra ID.

## Scenario

This lab simulated the three key moments of an employee's lifecycle within an organization: joining, transferring departments, and leaving, and the identity changes each one requires.

## Tasks Completed

- **Joiner:** Reviewed users who had joined the organization in Entra ID.
- **Mover:** Removed Kyle Roberts from IT-Staff-Sec-Group and added him to HR-Staff-SecGroup, then updated his job title to HR Specialist to reflect his transfer from IT to HR.
- **Leaver:** Deleted Kyle Roberts' user account, confirmed the deletion, and verified the account appeared in the Deleted users view within the recoverable 30-day deletion window.

## Screenshots

<p align="center">
<img width="1000" alt="Users who joined the organization" src="https://github.com/user-attachments/assets/044ebe3b-b669-4c11-8ea7-1c4f6c6a8650" />
</p>
<p align="center"><em>Joiner: users that have joined the organization.</em></p>

<p align="center">
<img width="700" alt="Kyle Roberts in IT-Staff-Sec-Group" src="https://github.com/user-attachments/assets/93b9608e-843a-40e5-8d2a-d07ca3de0885" />
</p>
<p align="center"><em>Mover: Kyle Roberts starting in IT-Staff-Sec-Group.</em></p>

<p align="center">
<img width="700" alt="Removing Kyle Roberts from IT-Staff-Sec-Group" src="https://github.com/user-attachments/assets/a4483c68-b07d-4d95-a0d9-5c6017e470fa" />
</p>
<p align="center"><em>Mover: removing Kyle Roberts from IT-Staff-Sec-Group.</em></p>

<p align="center">
<img width="700" alt="Selecting HR-Staff-SecGroup for Kyle Roberts" src="https://github.com/user-attachments/assets/f96f3135-5a72-4d40-97c0-07d2420be2ca" />
</p>
<p align="center"><em>Mover: adding Kyle Roberts to HR-Staff-SecGroup.</em></p>

<p align="center">
<img width="700" alt="Kyle Roberts job title changed to HR Specialist" src="https://github.com/user-attachments/assets/09cac97d-6dbd-45cd-a8d1-f6f460e7d2bd" />
</p>
<p align="center"><em>Mover: job title updated to HR Specialist, reflecting the move from IT to HR.</em></p>

## Skills Demonstrated

- Identity Lifecycle Management
- Account Deprovisioning
- Group and Attribute Management
- Offboarding Procedures

## What I Learned

This lab made clear that identity management isn't a one time setup. Accounts need to be actively updated as people change roles, and properly deprovisioned (not just ignored) when they leave, including understanding the recovery window before permanent deletion.

## Lab Environment

- Microsoft Azure Entra ID
- Windows 11
