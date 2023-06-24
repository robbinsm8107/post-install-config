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

- Configure Roles, Departments, and Teams
- Set up Permissions 
- Configure Users and Agents
- Set up Service Level Agreements (SLAs)
- Set up Help Desk Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/Hp3h1ia.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/HQTM6oI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/lDcGWo4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
Once the osTicket application is set up and running properly within the virtual machine, we then set up a few example Roles, Departments, and Teams. This is a critical step to take in the creation of permissions and to ensure that security would be set up on a "needs to know" basis. The Roles are set up in a way where you would have varying levels of access/ability to see and interact with the various ticket levels. The lowest level would be "read-only" whereas the "Supreme Admin" role would have absolute access to anything and everything within osTicket. The Departments are set up so that certain tickets would go to specific Departments; the reason for this would be that the Maintenance Team has no reason to be receiving tickets for a Virtual Machine going down or a Virtual Private Network not working properly. It gives an additional level of order for the various processes that are needed to run a business. We then created Level I Support and Level II Support for a more enhanced breakdown of the various tickets that may come in. My thought process would be that maybe the Level I Support would be the end-user interaction that speaks directly with customers whereas the Level II Support would be more focused on escalations and projects. I believe that this is an oversimplification but shows many of the core components that need to be considered when creating a ticketing system like this.  </p><br />

<p>
<img src="https://i.imgur.com/gRfOJuQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/pkjznUo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We then created a couple of examples of Agents and Users. The Agents were set up with the idea to create a System Administrator and a Support User to test the functionality of the permissions that were created in the first paragraph. We then created a few test User accounts where they would not have access to the backend ticketing queue or system. These two accounts are set up to allow us to create tickets and go through the entire ticketing cycle within the next project. </p><br />

<p>
<img src="https://i.imgur.com/MRpBOCY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/GEp5I1q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
The entire point of this section would be the create Service Level Agreements (SLAs) and Help Topics. These two ideas would go hand in hand and would give Agents and Users a way to decide on prioritization of the issues that show up on the day-to-day. We would put much more emphasis on a Sev-A SLA where we set this up to have an answer within an hour and have shifts on 24/7 to monitor such issues. A Help Topic example of this would be the Business Critical Outage. If my client's company's entire website is down, then that is going to have much higher priority than resetting another Agent's password at this moment. This also helps prioritize what team members should be doing, where the System Administrator on Level II may have to stop their current project and shift focus directly to the Outage whereas Level I can continue to work on resetting passwords, answering requests for hardware/software and other examples of less critical issues that are still important.  </p>
<br />
