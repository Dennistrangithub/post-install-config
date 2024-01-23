<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

<ul>
  <li>Roles Configuration</li>
  <li>Department Setup</li>
  <li>Team Setup</li>
  <li>Agent Setup</li>
  <li>SLA Configuration</li>
  <li>Help Topics Setup</li>
</ul>

<h2>Role Configuration</h2>

<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/ba399b04-9689-4101-88cf-6a32ccd89bd9" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I accessed the Admin Panel in osTicket to create a new role named 'Supreme Admin.' This role is intended to have the highest level of access in the system. I set up the Supreme Admin with permissions that allow complete control over all areas of the ticketing system, including user and ticket management, as well as system settings. The aim was to ensure this role could manage everything smoothly while keeping the system secure.
</p>
<br />

<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/b5dcfff1-0939-47b5-ac95-b425e0dfdae4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I added 'Supreme Admin' as a new role in osTicket through the Admin Panel. This role was given all permissions, ensuring complete access and control over the entire system.
</p>
<br />

<h2>Department Setup</h2>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/c8eaa557-7974-45d6-ba3c-0d19e624ab9b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/3eddc129-977b-4e5c-9821-afc2f16b1cad" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
I navigated to the Department Panel in osTicket and created a new department named 'System Administrators.
</p>
<br />

<h2>Team Setup</h2>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/1646e110-4231-457e-bcb0-43ff5b256f72" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/4d2d6b06-4757-48af-8786-784f183221a4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
I proceeded to create teams in the Ticketing System, including one named 'Support II.
</p>
<br />

<h2>Member Setup</h2>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/5ec82e41-7822-4c43-94df-46b8a90d2369" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/317599b0-25f2-446e-9aaa-3a7405b5cf3d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
I then created team members within the system and assigned them to various departments. The first team member was added and specifically assigned to one of the newly created departments
</p>
<br />

<h3>2nd Person</h3>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/a1c5e416-ca5f-45d0-ac49-5105aa83de39" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/1a3bd1fe-09c2-41ae-9cbc-263f0d0257b7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/993ed4c7-7ca7-41ed-8232-381c1fb72242" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
For the second team member, I assigned them to a department I had previously added and also included them in the support team
</p>
<br />

<h2>SLA Configuration</h2>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/bbb36339-5fed-4cc5-a4d4-9b8b1e2158cb" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
At this stage, I configured the SLA settings in osTicket, tailoring them based on the severity of the problems reported.
<li>SEV-A (Grace period is 1 hour within a 24/7 schedule)
<li>SEV-B (Grace period within a 4-hour window within a 24/7 schedule)
<li>SEV-C (A grace period of 8 hours within a 9/5 schedule)
</p>

<h2>Help Desk Topics</h2>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/730dcbc0-6360-4508-8d62-9cdfa0d93355" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
In this phase, I added selectable help topics to osTicket, allowing users to specify their particular issues when submitting tickets. Each topic was assigned a priority level and an SLA importance. The highlighted topics are those I added and configured, while the others are the default ones included in the system.
</p>

<h1>osTicket - Post-Install Configuration (Conclusion) </h1>
The post-installation configuration of osTicket has been a comprehensive and enlightening experience. This process included crucial steps like Roles Configuration, Department Setup, Agent Setup, SLA Configuration, and Help Topics Setup. Each of these objectives played a vital role in ensuring the osTicket system was tailored to meet the specific needs of our support structure.

Through role configuration, I learned the importance of clearly defining permissions and access levels for different users within the system. This step was crucial in maintaining an organized and secure support environment.

In setting up Departments, the experience highlighted the need for structured segmentation of support areas. This organization allows for more efficient handling of tickets and better allocation of resources.

Agent Setup provided insights into the significance of correctly assigning roles and departments to each agent. This ensures that every support query is directed to the right individual with the relevant expertise.

SLA Configuration was a key learning area, emphasizing the importance of establishing clear expectations for response and resolution times. This step is vital in maintaining customer satisfaction and trust.

Lastly, developing Help Topics was a lesson in resource management and user self-service. By providing easily accessible information, we can reduce the volume of support tickets and empower users to find solutions independently.

Overall, this journey through the post-installation configuration of osTicket has not only equipped me with practical skills in setting up a support ticket system but also provided valuable insights into the principles of effective IT support management.
