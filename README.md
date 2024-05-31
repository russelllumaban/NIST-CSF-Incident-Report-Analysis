<h1>Security Audit Practice</h1>


<h2>Description</h2>
Project consists of creating an incident report using knowledge of the NIST Cybersecurity Framework.
<br />


<h2>Scenario</h2>
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
<br />
<br />
During the attack, your organization's network suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services.
<br />
<br />
The company's cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company's network through an unconfigured firewall. The vulnerability allowed the malicious attacker to overwhelm the company's network through a distributed denial of service (DDoS)
<br />
<br /> 
To address this security event, the network security team implemented:
<br />
  -A new firewall rule to limit the rate of incoming ICMP packets
<br />
  -Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
<br />
  -Network monitoring software to detect abnormal traffic patterns
<br />
  -An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics
<br />
<br />
As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company's network security, following the NIST Cybersecurity Framework. You will use the CSF to help you navigate through the different steps of analyzing cybersecurity events and integrate your analysis into a general security strategy.
<br />


<h2>Program walk-through:</h2>

<p align="center">
Summary: <br/>
<img src="https://imgur.com/ZKjHdMk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Identify:  <br/>
<img src="https://imgur.com/8GoXLbQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Protect: <br/>
<img src="https://imgur.com/Dmqgj2H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Detect:  <br/>
<img src="https://imgur.com/FVg7xya.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Respond:  <br/>
<img src="https://imgur.com/CwZ5KvA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Recover:  <br/>
<img src="https://imgur.com/szVM8mG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
