<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket web-application

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure different functions of osTicket to create an infrastructure that mimics a help desk environment. We will use this setup to demonstrate a ticket's lifecycle in the next project. 

<h2>Configuration Steps</h2>

  1. Configure Role
     
     Configure roles for grouping permissions. Create a role called "Supreme Admin" and enable all permissions. 

  ![image](https://github.com/user-attachments/assets/5664a755-18dd-4304-9413-a03dc8434907)

  2. Configure Departments

     Create a department called SysAdmins.

  ![image](https://github.com/user-attachments/assets/f87b10f4-6f60-4a17-a389-356474dba46c)
 
  4. Configure Team

     Create a new team called "Online Banking". Team can consist of agents from different departments.

  ![image](https://github.com/user-attachments/assets/daee03ea-6d3d-4181-ae16-2cfacfa3f27e)

  5. Configure Agents

     Create two agents and place them in appropriate departments with permissions. Agents are the help desk workers. (Fill in the credentials and remember them) 
     - Jane Doe (Dept: SysAdmins)
     - John Doe (Dept: Support)
       
  ![image](https://github.com/user-attachments/assets/9cfe82d6-4a68-42c9-89da-79334f2a9b32)

  ![image](https://github.com/user-attachments/assets/7c93b70e-69e4-46c7-9e8e-6525c3a5ccb9)

  5. Configure Users

     Create two users. Users are customers who will be creating tickets. (Remember the credentials)
       - Karen
       - Ken
  ![image](https://github.com/user-attachments/assets/0748fe38-c4a1-4595-ade6-a89eb2ea0fe6)

  ![image](https://github.com/user-attachments/assets/3953a161-40ad-4b08-8fa1-057f9b89b65a)

  6. Configure SLA

     Admin Panel -> Manage -> SLA. Create 3 categories of SLA.
       - Sev-A (Grace Period: 1 hour, Schedule: 24/7)
       - Sev-B (Grace Period: 4 hours, Schedule: 24/7)
       - Sev-C (Grace Period: 8 hours, Business Hours)
  
  ![image](https://github.com/user-attachments/assets/6b29814c-fd83-4855-adc5-0563b792682e)

  ![image](https://github.com/user-attachments/assets/b1aa15fa-48f2-4841-84ea-56c2315027dc)

  7. Configure Help Topics

     Create Help Topics for when users create tickets. Admin Panel -> Manage -> Help Topics.
       - Business Critical Outage
       - Personal Computer Issues
       - Equipment Request
       - Password Reset
       - Other
         
  ![image](https://github.com/user-attachments/assets/8b9992b5-2b5d-4651-9c02-8af65d17b875)

</p>



