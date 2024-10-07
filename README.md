<h1>NIST Cybersecurity Framework Incident Response Project</h1>

 ### [Full Incident Report Google Doc](https://docs.google.com/document/d/1VnZ5DE64zAAB0Y-hQyW3_z5BVT-au3zCdbFurQLb_Eg/edit?usp=sharing)

<h2>Description</h2>
In this project, I managed a DDoS attack that exploited an unconfigured firewall, causing a two-hour network disruption. After restoring services, I was tasked with developing a security improvement plan using the NIST Cybersecurity Framework, including firewall updates, IP verification, and monitoring tools.
<br />

<h2>Scenario</h2>

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

    A new firewall rule to limit the rate of incoming ICMP packets

    Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

    Network monitoring software to detect abnormal traffic patterns

    An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

<br />

<h2>Program walk-through:</h2>

<p align="center">
Summarize the security event: <br/>
<img src="https://i.imgur.com/UxvaJ9N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Identify the type of attack and the systems affected:  <br/>
<img src="https://i.imgur.com/XTDM5wG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Protect the assests of your organization from being compromised: <br/>
<img src="https://i.imgur.com/hEIYDem.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Detect similar incidents in the future:  <br/>
<img src="https://i.imgur.com/6UHqqmL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Respond to future cybersecurity incidents:  <br/>
<img src="https://i.imgur.com/JgkP7Tu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Recover from the incident:  <br/>
<img src="https://i.imgur.com/So5NoOL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>
