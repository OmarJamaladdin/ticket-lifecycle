<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- End-user Ticket Creation
- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

![image](https://github.com/OmarJamaladdin/ticket-lifecycle/assets/140512686/64ac46e0-d64b-4493-8ae6-744f4a680531)

</p>
<p>
Here I am creating tickets as an end-user of osTicket.com. These tickets will be submitted to osTicket and I will then receive and solve  these tickets as a help desk professional on the other end.
<br />

![image](https://github.com/OmarJamaladdin/ticket-lifecycle/assets/140512686/0e35139b-303b-41fe-8598-d8ddaf52599f)

</p>
Here is the intake process of the ticket I created earlier from Karen (End-User). In this screenshot I am now Jane Doe (Sys Admin). I have received the ticket and made changes to the ticket due to the severity of the ticket that the end-user wasn't aware of. Customers not being able to use online banking is a serious issue so I set the priority of the ticket to 'EMERGENCY" and set the SLA or (Service Level Agreement) to Sev-A. Meaning the ticket must be solved within 1 hour of receiving it.
</p>

![image](https://github.com/OmarJamaladdin/ticket-lifecycle/assets/140512686/32f1ffeb-052e-4dee-a512-f77ff5139266)

Here I am still Jane (Sys Admin). Again,  I upgraded the priority level of this ticket to what I deemed neccessary (high) and I also reset the SLA to SEV-B. However, this time I assigned the ticket to agent John Doe via Warm Handoff (meaning we had communication and the assignment was acknowledged. This way he can work the issue and find a resolution. While Jane(Sys Admin) handles more severe concenrns.

![image](https://github.com/OmarJamaladdin/ticket-lifecycle/assets/140512686/dbabc12d-a2b1-4681-84c0-e7affd7088b8)

Here is an example of working the issue. Here, John Doe (Help desk agent) has found a temporary solution to roll back everyone's version of Adobe Reader. Doing this allows everyone to still have access and use a functioning version of Adobe reader. Although it's not the latest version, what's more important is that the program functions for everyone. In the meantime, John will work to find a solution to make the new version of Adobe reader work for everyone.

![image](https://github.com/OmarJamaladdin/ticket-lifecycle/assets/140512686/539c574b-6cd3-4b8a-9d0d-d6a157068880)

Finally, John (Help Desk Agent) has managed to find a solution as to why the new version of Adobe Reader wouldn't work for anyone in the department. He then upgraded everyone's Adobe Reader again and left an explanation of this in osTicket prior to resolving and closing the ticket. This way everyone is on the same page (Jane (sys admin)) and this ticket can be used as an example in the future to help new Help Desk technicians who come across this same issue.
