<p align="center"><a href="https://support-ui.webmelvin.me" target="_blank"><img src="https://raw.githubusercontent.com/melvin78/TicketCRM/master/ticket.png" width="400"></a></p>


# Helpdesk Solution 

A web based support portal to help keep track of issues and queries between clients
and agents. Scroll to View Demo section to interact with the system.
The system has two components:

## Features
- Automatic Email Notifications after ticket creation,transfer and assignment.With the help of [Mail Gun](https://www.mailgun.com/)
- Realtime chats between agent and client with the help of websockets. Using [Pusher](https://pusher.com/) service.
- Data upload and retrieval with the help of Digital Ocean's Space similar to Amazon's AWS bucket.
- Background Tasks that automatically assign tickets to agents using .NET's IHostedService implementation.
- Uses .NET Core's OIDC protocol for Authentication i.e IdentityServer


#  Process Flow
On logging in users raise an issue based on pre-defined enquiry categories.
After an issue is raised its assigned a unique ticket number that will then be used to
track the issue until when it is resolved. They also give a ticket priority on how severe the issue is.



#### Creating a Ticket

After successfully logging in you will be directed to the dashboard. Here you can open a ticket,
view history of all closed tickets and recently opened Tickets. You can also view the status of your tickets
whether it has been assigned to an agent, transferred to a different agent or has been resolved. Open chat with an agent in order to get assistance.


Dashboard
<img src="https://raw.githubusercontent.com/melvin78/TicketCRM/master/main-support.png" alt="here">

Ticket History
<img src="https://raw.githubusercontent.com/melvin78/TicketCRM/master/ticket-history.png" alt="here">

Previous Tickets
<img src="https://raw.githubusercontent.com/melvin78/TicketCRM/master/previous-tickets.png" alt="here">

Open Chats
<img src="https://raw.githubusercontent.com/melvin78/TicketCRM/master/chat.png" alt="here">




# View Demo
Dem can be found [here](https://support-ui.webmelvin.me/)
