<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Ticket Lifecycle Examples</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. This tutorial assumes you have completed both the <a href= "https://github.com/joshuafinchCC/osticket-prereqs"> installation </a> and <a href = "https://github.com/joshuafinchCC/osticket-installation">configuration</a> of osTicket

</br>

<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
  <li>osTicket</li>
</ul>

</br>
<h2>Operating Systems Used </h2>
<ul>
  <li>Windows 10</li>
</ul>
</br>
<h2>Ticket Lifecycle Stages</h2>
<ol>
  <li>Recieving your first Tickets</li>
  <li>Assignment & Communication</li>
  <li>Working Tickets</li>
  <li>Closing and Archiving tickets</li>
</ol>

</br>

<h2>Lifecycle Stages</h2>
<h3>Intake</h3>

<p>
  <ul>
    <li>From the <b>End User</b> portal, We're gonna pretend to be our already created(Steve Stevenson), creating a ticket and filling out some basic information</li>
    <ul>

 <p align="center">
        <img src="https://github.com/joshuafinchCC/osticket-examples/assets/155266044/a6b218f9-1b47-4333-a00c-ad9ba606ab15" height="80%" width="80%">
        </p>
       </ul>
    <li>After filling out the  subject and details of the ticket, we simple select <b>Create Ticket</b> </li>
    <li>The ticket is then sent to <b>Agent</b> Determination (which we've set as System Administrator is able to see all incoming tickets in the configuration tutorial) who views it from the <a href = "http://localhost/osTicket/scp/login.php">local help desk login</a></li>
    <ul>
      <li><b>Note</b>: Priorities have not been set for other incoming tickets. SLA plans need to be set for these tickets hence why they are all under the priority state of "Normal"</li>
       </ul>
 <p align="center">
  <img src="https://github.com/joshuafinchCC/osticket-examples/assets/155266044/dbe0cbab-4cae-49ae-b625-224ddbea7808" height="80%" width="80%">
   </p>

<h3>Assignment & Communication</h3>

<p>
  <ul>
    <li>Now lets observe this banking system ticket since it definately seems business critical. Here we can set the priority, assign the ticket, and even message the user directly with updates at the bottom of the ticket page</li>
 </ul>

<p align="center">
  <img src="https://github.com/joshuafinchCC/osticket-examples/assets/155266044/b3c233d3-6d4a-485c-84a0-b6c970db625a" height="80%" width="80%">
   </p>
     
<li>As Agent Determination makes changes to the priority and department of the ticket, osTicket tracks all the updates and notes made.</li>
   <p align="center">
  <img src="https://github.com/joshuafinchCC/osticket-examples/assets/155266044/0f1a3e08-c286-4a49-a3ff-b44809bc8559" height="80%" width="80%">
   </p>
    
  <li>The Agent can message the End User through the Ticket Thread to update the User on the ticket as well as set the status of the ticket (which is left as <b>Open</b> since we need to work it out)</li>
  
<p align="center">
  <img src="https://github.com/joshuafinchCC/osticket-examples/assets/155266044/81670b00-d732-4b43-9588-7b7768abf348" height="80%" width="80%">
   </p>

<br />

<h3>Working the Issue and Resolution</h3>

<p>
  <ul>
    <li>Following from our Assignment of Departments and Communication with the End User, the issue in our hypothetical Critical Banking Outage ticket has been resolved thanks to System Engineering. The Agent should now communicate the issue with the End User using the Ticket Thread and set the status of the ticket from Open to <b>Resolved</b>. Upon posting the Reply, the ticket is <b>Closed</b>.</li>
    <ul>
      <li><img src="https://github.com/ColtonTrauCC/ticket-lifecycle/assets/147654000/fa08856b-4eb5-430b-ac76-ca606e494229" height="80%" width="80%" alt="Disk Sanitization Steps"/></li>
    </ul>
    <li>Closed tickets can be found under the Closed section in our Tickets tab, where information and status of the tickets are archived. It is good practice for Agents to study Closed tickets to improve their experience in working with them</li>
    <ul>
      <li><img src="https://github.com/ColtonTrauCC/ticket-lifecycle/assets/147654000/2e3b4963-5ca7-4d82-a004-17d2c166c8a0" height="80%" width="80%" alt="Disk Sanitization Steps"/></li>
    </ul>
  </ul>
</p>

<br />
