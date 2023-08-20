<h1>Use the NIST Cybersecurity Framework to respond to a security incident. 
<h2>Description</h2>
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. The organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

- <b>A new firewall rule to limit the rate of incoming ICMP packets</b>
- <b> Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets</b>
- <b> Network monitoring software to detect abnormal traffic patterns</b>
- <b> An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics


As cybersecurity ananlysts, we must create a plan to improve the company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF).

<h2>Incident report analysis - Example</h2>

![Screenshot 2023-08-20 5 43 57 PM](https://github.com/mmedinabet/Use-the-NIST-Cybersecurity-Framework-to-respond-to-a-security-incident/assets/142737434/76ae6e10-cf9f-48ac-af63-bafbe921a87d)


Summary
- <b>This morning, an intern reported to the IT department that she was unable to log in to her internal network account. Access logs indicate that her account has been actively accessing records in the customer database, even though she is locked out of that account. The intern indicated that she received an email this morning asking her to go to an external website to log in with her internal network credentials to retrieve a message. We believe this is the method used by a malicious actor to gain access to our network and customer database. A couple of other employees have noticed that several customer records are either missing or contain incorrect data. It appears that not only was customer data exposed to a malicious actor, but that some data was deleted or manipulated as well. The cybersecurity team found the disruption was caused by a distributed denial of services (DDoS) attack through a flood of incoming ICMP packets.</b>



Identify
- <b> The incident management team audited the systems, devices, and access policies involved in the attack to identify the gaps in security. The team found that an intern’s login and password were obtained by a malicious attacker and used to access data from our customer database with an ICMP flood attack. Upon initial review, it appears that some customer data was deleted from the database. </b>


Protect
- <b> The team has implemented new authentication policies to prevent future attacks: multi-factor authentication (MFA), login attempts limited to three tries, and training for all employees on how to protect login credentials. Additionally, we will implement a new protective firewall configuration and invest in an intrusion prevention system (IPS).</b>


Detect 
- <b> To detect new unauthorized access attacks in the future, the team will use a firewall logging tool and an intrusion detection system (IDS) to monitor all incoming traffic from the internet.</b>

Respond 
- <b> The team disabled the intern’s network account. We provided training to interns and employees on how to protect login credentials in the future. We informed upper management of this event and they will contact our customers by mail to inform them about the data breach. Management will also need to inform law enforcement and other organizations as required by local laws. </b>


Recover
- <b> The team will recover the deleted data by restoring the database from last night’s full backup. We have informed staff that any customer information entered or changed this morning would not be recorded on the backup. So, they will need to re-enter that information into the database once it has been restored from last night’s backup.  </b>
  

