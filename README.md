<h1>Wazuh Siem Homelab</h1>



<h2>Description</h2>
This home lab simply illustrates how we can install a WAZUH instance on a cloud provider service which is called Linode and it is then configured as a SSH connection or we can apply Reverse DNS to open the interface in our browser. Additonally, we add the new agents in our Wazuh manager as that could be our Window Machine, Linux Machine or any other host machine agent we want to monitor and control. To summarize, this SIEM tool has numerous advantages in the field of cybersecurity as not only does it help to monitor the anomalies, vulnerabilities, data and network events it also helps in automating the responses in the desired way efficiently.
<br />


<h2>Environments/Tools Used</h2>

- <b>Linode Cloud Provider</b> 
- <b>Wazuh </b>
- <b>Windows Powershell</b>

<h2>Program walk-through:</h2>

<p align="center">
<br />
 
Installing the Wazuh instance through Linode Cloud provider: 
 
 <br/>
 <img src="https://imgur.com/ez28QqM.png" height="80%" width="80%" "/>
<br />
<br />
 Deploying a new Wazuh agent from the portal:
<img src="https://imgur.com/C1hX2Xy.png" height="80%" width="80%" />
<br />
<br />
Installing the wazuh configuration with Windows powershell on Windows 11 agent: <br/>
<img src="https://imgur.com/9Hy24zZ.png" height="80%" width="80%" />
<br />
<br />
Staring the Wazuh service on the agent:  <br/>
<img src="https://imgur.com/qzwMFS4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Two agents deployed as wazuh agents :- Windows Machine and Kali Linux :  <br/>
<img src="https://imgur.com/rzU7LVR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Security configuration assessment of agent  <br/>
<img src="https://imgur.com/EbqGCS2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Security Configuration assessment  <br/>
<img src="https://imgur.com/LcnBwQ9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Editing the OSSEC.confg file for active response on rule based Wazuh detection and i also changed the time from 180 to 30 just to block a user after an invalid authentication  <br/>
<img src="https://imgur.com/lTb66Ck.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Editing the configuration file to alter the Vulnerability assessment check to YES  <br/>
<img src="https://imgur.com/kU6lpM8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


                                 
                                 END OF THE PROJECT.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
