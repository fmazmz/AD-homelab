## Post-Compromise - Defence Overview
Looking back at the Event Viewer on the domain controller, we can find the following events being logged in the domain controller during the different attacking stages of the pentest.

### NTLM Authentication
While conducting pass-the-hash attacks on the clients we could see the following event being logged in the system:
![NTLM Warning](/NTLM_warning.png)

