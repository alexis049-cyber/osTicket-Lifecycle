<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

This document provides a step-by-step guide to creating and managing tickets within the osTicket system to demonstrate their lifecycle. Each scenario includes steps for creating tickets, observing their properties, setting their attributes, and working them to completion.

Admin/Analyst Login (controller)

End Users osTicket (user)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2 Gen 2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Before you Start</h2>

Disable/Delete Maintenance Department so tickets don't end up there.
To do this:
  - Navigate to Admin Panel -> Agents -> Departments.
  - Click on Maintenance and delete
<img width="1394" height="434" alt="image" src="https://github.com/user-attachments/assets/e788ecc3-4bcc-4ead-b3a6-d11271b83075" />


<h2>Scenarios</h2>

<h3> Scenario 1: Entire Mobile/Online Banking System is Down</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: [http://localhost/osTicket](http://localhost/osTicket)
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: Entire Mobile/Online Banking System is Down
  - Details: Provide a brief description of the issue.
 
<img width="1108" height="1294" alt="image" src="https://github.com/user-attachments/assets/22311c67-fd69-4c65-9a3c-71169861b694" />


**As a Help Desk Agent (John)**
- Navigate to the Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- Log in as "john."
- Locate the newly created ticket and observe its properties:
  - Priority
  - Department
  - SLA
  - Assigned To
- Set the ticket properties as follows:
  - Priority: Sev-A (1 hour, 24/7)
  - Department: Online Banking Department
- Attempt to observe the ticket again as "john" and note whether you can view or change it.

<img width="1398" height="512" alt="image" src="https://github.com/user-attachments/assets/74bcb188-2818-478f-9aef-f33a580c09c5" />
<img width="1442" height="674" alt="image" src="https://github.com/user-attachments/assets/90d71a92-3e64-4790-927d-59a76e47a4b1" />
<img width="1234" height="692" alt="image" src="https://github.com/user-attachments/assets/06da89ec-97e7-4d6e-87c9-097e1e102b6e" />
<img width="1290" height="576" alt="image" src="https://github.com/user-attachments/assets/97059c49-b3ff-4ed1-9a24-96fc1abf6d2c" />

**As a Help Desk Agent (Jane)**
- Log in as "jane."
- Work the ticket to completion.

<img width="1012" height="644" alt="image" src="https://github.com/user-attachments/assets/c9a7c9ce-a34a-407d-b2f4-2db537d8c5ef" />
<img width="1120" height="526" alt="image" src="https://github.com/user-attachments/assets/cd35bdd2-527b-4bbe-b7f0-8525bf5bba34" />
<img width="1366" height="902" alt="image" src="https://github.com/user-attachments/assets/5fe9e543-08c1-401c-a875-4ac2f32c0d52" />
<img width="1430" height="1054" alt="image" src="https://github.com/user-attachments/assets/661c6627-d784-4161-87b8-ec902da64787" />
<img width="1388" height="948" alt="image" src="https://github.com/user-attachments/assets/7d781d16-a746-472b-8137-67c2cb91351a" />
<img width="1032" height="374" alt="image" src="https://github.com/user-attachments/assets/12bce449-3657-4fb5-8e3d-b37a8d23b4ea" />

<h3>Scenario 2: Accounting Department Needs Adobe Upgrade, Broken</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: http://localhost/osTicket
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: Accounting Department Needs Adobe Upgrade, Broken
  - Details: Provide a brief description of the issue.

<img width="1172" height="1246" alt="image" src="https://github.com/user-attachments/assets/822bdb21-67dd-454c-97b8-66cf0e000478" />


**As a Help Desk Agent (John)**
- Navigate to the Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- Log in as "John."
- Locate the newly created ticket and observe its properties:
  - Priority
  - Department
  - SLA
  - Assigned To
- Set the ticket properties as follows:
  - Priority: Sev-B (4 hours, 24/7)
  - Department: Support
- Work the ticket to completion.

<img width="1462" height="894" alt="image" src="https://github.com/user-attachments/assets/614efe6e-72ce-47b3-b805-490c44e06e42" />
<img width="1188" height="460" alt="image" src="https://github.com/user-attachments/assets/da65e0e7-bcb2-494c-8e97-2197ee8aaddf" />
<img width="1034" height="422" alt="image" src="https://github.com/user-attachments/assets/f77c42f4-841c-4fcc-882b-0944302f9ade" />
<img width="1336" height="906" alt="image" src="https://github.com/user-attachments/assets/7d97c3c3-19e8-427e-ba18-5a80e1994229" />
<img width="1318" height="856" alt="image" src="https://github.com/user-attachments/assets/909862e1-4800-4b65-b509-8be11411bf38" />
<img width="1004" height="334" alt="image" src="https://github.com/user-attachments/assets/c78ebff4-a27f-4f80-b8de-15577bfb2338" />


<h3>Scenario 3: CFO’s Laptop Will No Longer Turn On</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: http://localhost/osTicket
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: CFO’s Laptop Will No Longer Turn On
  - Details: Provide a brief description of the issue.

<img width="1216" height="1226" alt="image" src="https://github.com/user-attachments/assets/60a7b53c-d9e2-4113-8c4d-29c181729afd" />

**As a Help Desk Agent (John)**
- Navigate to the Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- Log in as "John."
- Locate the newly created ticket and observe its properties:
  - Priority
  - Department
  - SLA
  - Assigned To
- Set the ticket properties as follows:
  - Priority: Sev-B (4 hours, 24/7)
  - Department: Support
- Work the ticket to completion.

<img width="1374" height="444" alt="image" src="https://github.com/user-attachments/assets/bb44b5f8-fcde-4a12-8828-725401d7f96b" />
<img width="1342" height="636" alt="image" src="https://github.com/user-attachments/assets/bea632cd-0a88-4ea3-ae9c-c1cfabad7942" />
<img width="1098" height="486" alt="image" src="https://github.com/user-attachments/assets/4e680f5f-624c-40ae-a29e-d532590069b9" />
<img width="1368" height="1112" alt="image" src="https://github.com/user-attachments/assets/8aa5b88d-3eaa-48df-b2f0-bd8a12563afb" />
<img width="1026" height="422" alt="image" src="https://github.com/user-attachments/assets/766ea28c-8657-4370-8cad-8c4637dd1296" />

<h2>Purpose </h2>
This repository serves as a practical guide and example of the lifecycle of a ticket within the osTicket system. By following these steps, users can better understand ticket creation, assignment, and resolution workflows in a help desk environment.
