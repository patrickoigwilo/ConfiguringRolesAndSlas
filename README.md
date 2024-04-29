<h1>How to Configure Roles and Service Level Agreements (SLAs) on osTicket</h1>

<h3>After installing the osTicket platform, the next step is configuring users' roles/permissions and the SLAs that guide ticket resolution.</h3>

<h4>- Admin Panel vs Agent Panel</h4>

osTicket has both an 'Admin' Panel and an 'Agent' Panel.  
The Admin Panel allows an admin user to set up the ticketing system, define roles and SLAs, and perform other administrative functions within the osTicket environment.  
While the Agent Panel allows an agent user to work and close tickets opened by clients.

![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/ae8f5877-89ca-4620-b226-f13fbcc7394c)



<h4>- What are Roles?</h4>

Roles are permissions that can be granted to Agents according to the departments to which they belong. Each Role comes with a set of permissions that can be enabled/disabled based on the user's Department. Examples of role permissions include:  
1. Assign (user can assign tickets to agents)
2. Close (user can close tickets)
3. Edit (user can edit tickets)
4. Delete (user can delete tickets) etc.

![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/0e84e226-cc67-4128-bde8-299398bd3174)

<h4>- What are SLAs?</h4>

SLAs or Service Level Agreements, from a Help Desk standpoint, are guidelines as to the length of time by which a help desk Administrator expects a ticket to be closed.

![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/ed54f64e-8994-4891-940e-710de1abab44)


<h1>Configuration Walk-through:</h1>

<h4>- To create and configure a 'Supreme Admin' role, for instance,</h4>

I clicked on Admin Panel --> Agents --> Roles, thus:

![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/de54aae7-8d8a-467e-a06c-3738f96d49f7)
![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/d203b5b3-116f-4992-8154-dc2652d0d158)
![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/cf6a1363-780c-490a-b0a1-90e1b4c0508b)

This Supreme Admin role was configured to do virtually everything from 'Assign' tickets to 'Transfer' tickets as shown above.

<h4>- To create and configure an 'Agent' role (Helpdesk Staff), for instance,</h4>

I clicked on, Admin Panel --> Agents --> Add New, thus:

![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/8cb62d10-f5c5-488e-afa1-f9d2e5308698)
![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/83e925fb-e959-454e-b853-a55ac1720c49)
![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/3f4994bc-6f2a-4297-8b62-ad71fbc30b33)
![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/3adf1cde-b362-4a52-b0a3-eafe779c57f9)

<h4>- To create and configure a 'User' role (Customer/Client), for instance,</h4>

I clicked on, Agent Panel --> Users --> Add User, thus:

![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/ebe9f2e9-adf8-45b2-bfa9-a27e746170ba)
![image](https://github.com/patrickoigwilo/ConfiguringRolesAndSlas/assets/162601853/13a8098f-0602-4b3c-8691-1d8adb70991c)

<h4>- Finally, to create and configure a Service Level Agreement (SLA), for instance,</h4>

I clicked on, Admin Panel --> Manage --> SLA, thus:
