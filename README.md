<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket: Ticket Lifecycle Examples</h1>

In this tutorial I will outline the process of creating tickets as end Users and subsequently resolve them as administrators in osTicket. I just want to pretend as I am some End users and open up a few tickets and then I will connect as a helpdesk worker to resolve those ticket just to have some experience using osTicket.

<h2>Objectives</h2>

-  More experience in Azure
-  Learn how to open a few tickets as Users in osTicketing system and play around
-  Learn how to respond to tickets as Admins or Agents and gain momentum
-  Gain a better understanding of all parts of ticketing system such as <b>Tickets properties, SLAs, Departments, Permissions</b> and <b>Users</b>.

<h2>Environments and Technologies Used</h2>

-  Microsoft Azure (Virtual Machines/Compute)
-  Remote Desktop
-  osTicket

<h2>Operating Systems Used</h2>

-  Windows 10 pro

<h2>List of Prerequisites</h2>

-  The only requirement for this lab is the completion of the <a href="https://github.com/danielbangm/post-install-config">previous part.</a>

<h2>Project steps</h2>

-  Step 1: Connect to osTicket as a User and Create a ticket

As a guest User created previously, I just click on "open a new ticket" and I created 4 different tickets using our 2 Users(guests) Ken and Karen.
![image](https://github.com/danielbangm/ticket-lifecycle/assets/22795502/f9da21ab-0e31-418b-80cd-b1e3298b1e1a)

-  Step 2: Connect to osTicket as a Helpdesk Agent and work on your tickets
  
Now I connect back to osTicket as helpdesk agent(Jane in this case) and I can see all the tickets created by users Karen and Ken 
![image](https://github.com/danielbangm/ticket-lifecycle/assets/22795502/96109d6a-2a53-4fbe-8db5-d6ea5419698d)

I notice that these tickets are not assigned to any agents yet. I guest in real world work environment there's some kind of queue manager who is going to go through the description of each ticket and assign to agents.
![image](https://github.com/danielbangm/ticket-lifecycle/assets/22795502/7ff1658c-25d0-4d11-8af3-c7c77715cab2)

Now I decided to assign one ticket (The entire mobile online system is down) to Jane and also changed the Severity of the SLA to Sev-A because that's an emergency that needs to be fixed ASAP
![image](https://github.com/danielbangm/ticket-lifecycle/assets/22795502/0ac12ae4-d215-4ea0-857e-10dd6ccb4ce0)

Also notice that any changes you make on that ticket creates automaticallt a sort of thread which is like the history of the ticket
![image](https://github.com/danielbangm/ticket-lifecycle/assets/22795502/e171df4f-71b5-47d2-8eab-e66f2928779b)

-  Step 3: Resolve my first ticket

After assigning a ticket to an agent, I will pretend like I know what to do to solve the issue of the customer and initiate a reply, then mark it as resolve. Now i can notice that ticket dissapeared from my tickets
![image](https://github.com/danielbangm/ticket-lifecycle/assets/22795502/1cdeca64-25a5-4197-b7b8-d8abf00dc239)

-  Step 4: Closing my first ticket

I logged out and logged back in as system admin and went to My ticket -> Closed. And from here I can see what tickets have been closed and who worked on that. In this case Jane resolved it
![image](https://github.com/danielbangm/ticket-lifecycle/assets/22795502/aa562a56-b288-4679-834e-1978a40ef13f)

<h2>Conclusion</h2>

During this Lab I have learnt how the osTicketing system works. I created tickets and solved one of them by assigning to the right departmetn, team and agent and also changed the SLA to make it urgent, I replied to thread and then resolved the ticket. It was fun to work on this projet and I gain a lot of hands-on 
