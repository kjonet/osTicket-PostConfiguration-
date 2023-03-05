<h1> osTicket - Post Configuration Setup </h1>

<p>This tutorial will walk you through post configuration setup for osTicket. In a real use-case setting, this would be done by a system administrator. </p>

<h3> Step 1:</h3>

<p>Once the initial installation is set up, you should now be able to log in as an administrator. You can use the following link to get you to the login screen: http://localhost/osTicket/scp/login.php  Go ahead and type in your credentials. </p>

</br>
<a href="https://imgur.com/xpet5VW"><img src="https://i.imgur.com/xpet5VW.png" title="source: imgur.com" /></a>
</br>

<h3> Step 2: </h3>

<p>We are going to create aganets for our team. To do this, make sure you are in the admins panel. You can tell which panal you're in by looking in the upper right hand corner. Right now, we are in the Agent panal. Click Admin panal and we will be directed to the admin page. </p>

</br>
<a href="https://imgur.com/kJRBCrY"><img src="https://i.imgur.com/kJRBCrY.png" title="source: imgur.com" /></a>
</br>

<p>Once there, select Agents, and then Roles. We are going to create a Supreme Admin. Click “Add new role” then enter the name of the role. Permissions are able to be modified but since we are creating a supreme admin, we will grant this role all permissions. </p>

<h3> Step 3: </h3>

<p> Under “Department” within the agents tab, we can create a new department. This is where agents are assigned a specific department. Here, we will create a “Systems Administrators” department where all Supreme Admins will live.</p>

</br>
<a href="https://imgur.com/Py0y7vl"><img src="https://i.imgur.com/Py0y7vl.png" title="source: imgur.com" /></a>
</br>

<a href="https://imgur.com/IZv9y8S"><img src="https://i.imgur.com/IZv9y8S.png" title="source: imgur.com" /></a>

</br>

<h3>Step 4: </h3>

<p>Next, a new team will need to be created. To do this, go to the Agents tab, select Teams and assign a name to your team. In this example, we will be creating 3 teams for level I, Level II, and Level 3 agents. Creating Teams is a good way to pull agents from different departments to help tackle specific issues. </p>

</br>
<a href="https://imgur.com/6wzfQWq"><img src="https://i.imgur.com/6wzfQWq.png" title="source: imgur.com" /></a>
</br>

<h3>Step 5:</h3>

<p>We will need to configure user settings to enable any user to submit a ticket. To do this, navigate to the Settings tab, select Users and check off  where it says “Require registration and login to create tickets” under the Athentication settings. </h3>

<h3>Step 6:</h3>

<p>Here we will create our Agents. To do this, go over to the Agents tab, and click “Add new agent”. Here is where you will create your agent information such as contact information, password setup, what department and team they’ll be in and configure certain permissions. </p>

<br>
<a href="https://imgur.com/cHF5ARA"><img src="https://i.imgur.com/cHF5ARA.png" title="source: imgur.com" /></a>
</br>

<h3>Step 7:</h3>

<p>Next, we’ll go ahead and configure some users. To do this you will need to switch to the Agents Panal in the upper right hand corner. Once at the Agent panal, go over to the Users tab and click “add new user”. Proceed to create the users profile. </p>

</br>
<a href="https://imgur.com/PtpM1c5"><img src="https://i.imgur.com/PtpM1c5.png" title="source: imgur.com" /></a>
</br>

<h3>Step 8: </h3>

<p>Back in the Admin panal, we will configure SLA’s or Service Legal Agreements. SLA’s will dictate the length of time in which the help desk administrator expects the ticket to be executed and closed. To create an SLA, go to the Manage tab, click SLA, and select “Add new SLA plan”. </p>

<br>
<a href="https://imgur.com/Wnyl7T5"><img src="https://i.imgur.com/Wnyl7T5.png" title="source: imgur.com" /></a>
</br>

<h3>Step 9:</h3>

<p>Lastly, we wil create help topics. Help topics can help catagorize tickets, making  it easier on both the users and the agents. For example, if a user is in need of a simple password reset, the help desk topic might be “Password Reset”. </p>

</br>
<a href="https://imgur.com/gWqwjsB"><img src="https://i.imgur.com/gWqwjsB.png" title="source: imgur.com" /></a>
</br>

Great! This concludes a basic admin configuration of osTicket! 

