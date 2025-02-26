#<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

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

<p>
  If you are continuing from that last tutorial remember to start your VM in Azure portal and reconnect to the VM with your installation osTicket.
</p>
<br />

![Artboard 1](https://github.com/user-attachments/assets/639d87a4-0b01-4b58-bd73-3655fe885d41)

<p>

  To start, we are going to log in and play the role of our end user Molly, and create a ticket using this link: EndUser. Click "Open a New Ticket". Fill in Molly's name and email (Molly@problem.com). The issue Molly is having is that the entire mobile/ banking system is down. So for the help topic, Molly chooses "report a problem". But the correct answer would be "Business Critical outage", often, end users don't know which topic to pick. Later in the tutorial, we will practice changing the help topic of a ticket.
</p>
<br />

![Artboard 2](https://github.com/user-attachments/assets/6f4fceab-fb61-4179-8281-a477aaaefd93)

<p>
Now that the ticket is created you can log in as Peter and will begin to process the ticket. Click on the ticket, and observe the ticket's:
  
  - Priority
  - department
  - SLA
  - Assign To
    
Next, in a real-life scenario, it is best to contact the person who created the ticket (preferably by phone call) to ask them questions to know the true severity of the issue. Such as, how many people are being affected and is it still an ongoing problem. Assuming everything that Molly has said is true click on the SLA plan and change it to Sev-A. For "reason" you can put "High Impact, customers are unable to do online banking." then click update. Next, click on the help topic and change it to "Business Critical Outage"
  
</p>
<br />

![Artboard 3](https://github.com/user-attachments/assets/e1d8b1db-60a7-4d76-9762-44bd69c365d9)

<p>
If you refresh the page the tickets thread should be updated with all of the changes to the ticket. Next, click "assign to" and change it to the online banking team. For "reason" you can put "Online banking is down, assigning to the online banking team." then click assign. Then log out of Peter's account.
</p>
<br />


![Artboard 4](https://github.com/user-attachments/assets/68e8a9ee-14ff-4130-b2c9-a3c459326ed4)

<p>
We will continue working on the ticket as Dawn, who we assigned to the banking team earlier. Log in as Dawn and see that the ticket should now be assigned to the online banking team. But now that Dawn is working on the ticket assign it to her. Reasoning can be "I will be taking this ticket." Next down in "Post Reply" write a hypothetical response to the ticket such as "I believe the issue is caused by a recent update to our software. We rolled it back, notified the issuer, and are waiting for a proper fix. Online banking should now be running correctly." Then click post. Next to status set the ticket to resolved.

  Congratulations you have completed your first ticket.
</p>
<br />

