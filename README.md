<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the process of creating and resolving a ticket within the open-source help desk ticketing system, osTicket. You will learn how to create a ticket as an end user and resolve it as an agent.
<br />
<h2>Before Starting, Finish:</h2>

[osTicket: Post-Installation Configuration](https://github.com/Kushaltho/post-install-config)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Intake</h3>

First make some tickets as end users via http://localhost/osTicket/. Login in through the credentials you had made for the users in the last part.

For example Zuquan might have been getting lots of reports of 404 errors. 

<img src="https://i.imgur.com/kAA387C.png" width="80%" alt="Searching for VM"/>

Create two more tickets out of the help topics like Personal Computer Issues ,General Inquiry, Equipment Request, Password reset. Can also use different users. 

<img src="https://i.imgur.com/LDW6mPI.png" width="80%" alt="Searching for VM"/>
<img src="https://i.imgur.com/LbTXThm.png" width="80%" alt="Searching for VM"/>

<h3>Assignment and Communication</h3>

Now we are going to go through the tickets as an agent.

Go back to the agent panel using this link http://localhost/osTicket/scp/login.php with the credentials you made for the agent.



<img src="https://i.imgur.com/MJrLcal.png" width="80%" alt="Searching for VM"/>


<img src="https://i.imgur.com/3LrKHFP.png" width="80%" alt="Searching for VM"/>

Now our job as an agent would be to make sure that the tickets have the appropriate agent/worker and SLA/priority in the order of when it came.

If it can be resolved by the agent looking though the ticket then they can assign it to themself.



<img src="https://i.imgur.com/IEGp2to.png" width="80%" alt="Searching for VM"/>

<img src="https://i.imgur.com/mv73dgS.png" width="80%" alt="Searching for VM"/>

<img src="https://i.imgur.com/9L0i6oZ.png" width="80%" alt="Searching for VM"/>

<img src="https://i.imgur.com/h5eJttR.png" width="80%" alt="Searching for VM"/>



Since an entire department's work is impeded, the assignments should be high. And we will assign another agent for this ticket.


We will also assign one of the tickets to another agent as an agent.
<img src="https://i.imgur.com/n36IweR.png" width="80%" alt="Searching for VM"/>

<img src="https://i.imgur.com/zxOL8zh.png" width="80%" alt="Searching for VM"/>

This is what it would look like if everything was assigned properly. Although you would normally just work through the ticket all at once if possible.

<img src="https://i.imgur.com/ZAGpjyX.png" width="80%" alt="Searching for VM"/>






<h3>Working the Issue</h3>
SEV-A Ticket

<img src="https://i.imgur.com/tYLjqfW.png" width="80%" alt="Searching for VM"/>

SEV-B Ticket

Since we assigned the ticket to Eveyln it is best practice to write down the changes you made and give a warm hand-off to the person. Which would mean Kevin calling  Eveyln and confirming with her before assigning the ticket to her. 

<img src="https://i.imgur.com/7JUkgkn.png" width="80%" alt="Searching for VM"/>

<img src="https://i.imgur.com/jKMxxrv.png" width="80%" alt="Searching for VM"/>


<h3>Resolution</h3>


SEV-A Ticket


<img src="https://i.imgur.com/JithoNY.png" width="80%" alt="Searching for VM"/>

SEV-B Ticket

<img src="https://i.imgur.com/w1Dy9Ro.png" width="80%" alt="Searching for VM"/>

SEV-C Ticket

Since Kevin knew how to resolve the problem , he didn't need to assign it to someone else or give them an update while trying to figure out the solution.

<img src="https://i.imgur.com/KptsPvs.png" width="80%" alt="Searching for VM"/>

<h2>Finished</h2>
By completing this tutorial, you should now have a deeper understanding of osTickets and how they function from both the user and agent perspectives. You should also know how to configure user and agent settings to meet your needs, as well as how to effectively handle tickets as an agent.


