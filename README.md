# Infosec-Questions



## [General](##general)

### 1. What is information security and how is it achieved?

> Information Security is not only about securing information from unauthorized access. Information Security is basically the practice of preventing unauthorized access, use, disclosure, disruption, modification, inspection, recording or destruction of information.


### 2. What are the core principles of information security?

Information Security programs are build around 3 objectives, commonly known as CIA – Confidentiality, Integrity, Availability.

> Confidentiality – means information is not disclosed to unauthorized individuals, entities and process. For example if we say I have a password for my Gmail account but someone saw while I was doing a login into Gmail account. In that case my password has been compromised and Confidentiality has been breached.

> Integrity – means maintaining accuracy and completeness of data. This means data cannot be edited in an unauthorized way. For example if an employee leaves an organisation then in that case data for that employee in all departments like accounts, should be updated to reflect status to JOB LEFT so that data is complete and accurate and in addition to this only authorized person should be allowed to edit employee data.

> Availability – means information must be available when needed. For example if one needs to access information of a particular employee to check whether employee has outstanded the number of leaves, in that case it requires collaboration from different organizational teams like network operations, development operations, incident response and policy/change management.

**Example**
Denial of service attack is one of the factor that can hamper the availability of information.


### 3. What is non-repudiation (as it applies to IT security)?

> Non repudiation – means one party cannot deny receiving a message or a transaction nor can the other party deny sending a message or a transaction. For example in cryptography it is sufficient to show that message matches the digital signature signed with sender’s private key and that sender could have a sent a message and nobody else could have altered it in transit. Data Integrity and Authenticity are pre-requisites for Non repudiation.


### 4. What is the relationship between information security and data availability?

> Information security encompasses the tactics and processes used to protect data and ensure that only authenticated and approved users have access to authorized data.


### 5. What is a security policy and why do we need one?

The goal of these network security policies is to address security threats and implement strategies to mitigate IT security vulnerabilities, as well as defining how to recover when a network intrusion occurs.

### 6. What is the difference between logical and physical security? Can you give an example of both?

Logical security protects computer software by discouraging user excess by implementing user identifications, passwords, authentication, biometrics and smart cards. Physical security prevents and discourages attackers from entering a building by installing fences, alarms, cameras, security guards and dogs, electronic access control, intrusion detection and administration access controls. The difference between logical security and physical security is logical security protects access to computer systems and physical security protects the site and everything located within the site.


### 7. What’s an acceptable level of risk?

Acceptable risk is a risk exposure that is deemed acceptable to an individual, organization, or nation.


### 8. What are the most common types of attacks that threaten enterprise data security?

Denial-of-service (DoS) and distributed denial-of-service (DDoS) attacks. ...

Man-in-the-middle (MitM) attack. ...

Phishing and spear phishing attacks. ...

Drive-by attack. ...

Password attack. ...

SQL injection attack. ...

Cross-site scripting (XSS) attack. ...

Eavesdropping attack.


### 9. What is the difference between a threat and a vulnerability?

Threat is what an organization is defending itself against, e.g. a DoS attack. Vulnerabilities are the gaps or weaknesses that undermine an organization's IT security efforts, e.g.

### 10. Can you give me an example of common security vulnerabilities?



### 11. Are you familiar with any security management frameworks such as ISO/IEC 27002?



### 12. What is a security control?

Security controls are safeguards or countermeasures to avoid, detect, counteract, or minimize security risks to physical property, information, computer systems, or other assets. In the field of information security, such controls protect the confidentiality, integrity and availability of information.

### 13. What are the different types of security control?

Examples include physical controls such as fences, locks, and alarm systems; technical controls such as antivirus software, firewalls, and IPSs; and administrative controls like separation of duties, data classification, and auditing.

### 14. Can you describe the information lifecycle? How do you ensure information security at each phase?

Information lifecycle is the stage through which every (Written or computerized) record goes through from its creation to its final archiving or destruction. These stages may include change of format or recording media for easier access or more secure storage. ... We start with disconnected information.

we will briefly describe the Information Security Program lifecycle (Classification, Safeguarding, Dissemination, Declassification, and Destruction), why we need it, how it is implemented in the DoD and locate policies relevant to the DoD Information Security Program.

### 15. What is Information Security Governance?

IT security governance is the system by which an organization directs and controls IT security (adapted from ISO 38500). ... Governance specifies the accountability framework and provides oversight to ensure that risks are adequately mitigated, while management ensures that controls are implemented to mitigate risks.

### 16. What are your professional values? Why are professional ethics important in the information security field?

A code of ethics is important because it clearly lays out the rules for behavior and provides the groundwork for a preemptive warning. Regardless of size, businesses count on their management staff to set a standard of ethical conduct for other employees to follow.


### 17. Are open-source projects more or less secure than proprietary ones?

Proprietary software is more secure than open-source software. This myth comes from many prejudices. But a commercial license doesn't assure security. Unlike proprietary software, open-source software is transparent about potential vulnerabilities.


### 18. Who do you look up to within the field of Information Security? Why?



### 19. Where do you get your security news from?



### 20. What’s the difference between symmetric and public-key cryptography?

The basic difference between these two types of encryption is that symmetric encryption uses one key for both encryption and decryption, and the asymmetric encryption uses public key for encryption and a private key for decryption.

### 21. What kind of network do you have at home?



### 22. What are the advantages offered by bug bounty programs over normal testing practices?

One of the advantages of a bug bounty program is that it is continuous testing. A penetration test is typically a one-time assessment of your security at a point in time. While it gives you a good understanding of your security and the weaknesses of your network, it is only accurate while the network remains unchanged

### 23. What are your first three steps when securing a Linux server?

STEP 1 - Update your server. ...

STEP 2 - Disable root access via SSH. ...

STEP 3 - Change your SSH port. ...

STEP 3.5 - Use SSH Key-based Logins. ...

STEP 4 - Enable your firewall. ...

STEP 5 - Check for open ports. ...

STEP 6 - Install Fail2Ban. ...

STEP 7 - Disable responding to pings.

STEP 9 - Read your logs


### 24. What are your first three steps when securing a Windows server?

What	Why

1. User configuration -	Protect your credentials

2. Network configuration -	Establish communications

3. Features and roles configuration	Add what you need, remove what you don't

4. Update installation	Patch vulnerabilities

5. NTP configuration	Prevent clock drift

6. Firewall configuration	Minimize your external footprint

7. Remove access configuration	Harden remote administration sessions

8. Service configuration	Minimize your attack surface

9. Further hardening	Protect the OS and other applications

10. Logging and monitoring	Know what's happening on your system

11. Frequently asked questions	Common questions about server hardening

### 25. Who’s more dangerous to an organization, insiders or outsiders?

When asked, most cybersecurity experts will say that the insider threat is more serious because it's harder to detect. If a user has legitimate access to a company's files, it's not easy to see if they may be using that access for illegitimate purposes. Outsider risks are only slightly less serious.

### 26. Why is DNS monitoring important?

DNS stands for Domain Name System.

The pairing of the hostname and the IP address is called a namespace. Monitoring your DNS records helps you insure that the Domain Name System continues to route traffic properly to your websites, services, and electronic communications.

DNS has an important role in how end users in your enterprise connect to the internet. Each connection made to a domain by the client devices is recorded in the DNS logs. Inspecting DNS traffic between client devices and your local recursive resolver could reveal a wealth of information for forensic analysis.




### 27. How would traceroute help you find out where a breakdown in communication is?

Traceroute will shows every router (hop) that the packet reach while traveling from source to destination, it can show: 1- the hop causing the delay. 2- if there is a routing loop. 3- if the packet is taking unexpected/ unintended route

Tracert or traceroute, depending on the operating system, allows you to see exactly what routers you touch as you move along the chain of connections to your final destination. However, if you end up with a problem where you can’t connect or can’t ping your final destination, a tracert can help in that regard as you can tell exactly where the chain of connections stop. With this information, you can contact the correct people – whether it be your own firewall, your ISP, your destination’s ISP or somewhere in the middle.


### 28. Why would you want to use SSH from a Windows PC?

SSH is the de facto solution for securely accessing remote terminals on Linux and other UNIX-like systems. If you have a remote SSH server you want to access, you need an SSH client. SSH can be used for anything from remotely accessing a computer on your network to managing and backing up a website.

### 29. How would you find out what a POST code means?

The format of an HTTP POST is to have the HTTP headers, followed by a blank line, followed by the request body. The POST variables are stored as key-value pairs in the body.

Status codes are issued by a server in response to a client's request made to the server. ... All HTTP response status codes are separated into five classes or categories. The first digit of the status code defines the class of response, while the last two digits do not have any classifying or categorization role.


### 30. What is the difference between a black hat and a white hat?

Some hackers are criminals and use their computer skills to harm or damage computer systems. These people are called black hat hackers. White hat hackers, on the other hand, use their computer skills to perform ethical hacking. Ethical hacking can determine vulnerabilities in a computer system.

### 31. What do you think of social networking sites such as Facebook and LinkedIn?



### 32. Why are internal threats often more successful than external threats?

In general, insider threats can cause significant business impact, not only because of the privileges that employees have over information technology but also because the company theoretically has its employees under its control, being responsible for their actions, in contradiction to external threats.

### 33. Why is deleted data not truly gone when you delete it?

When you a delete a file, it isn't really erased – it continues existing on your hard drive, even after you empty it from the Recycle Bin. This allows you (and other people) to recover files you've deleted.

### 34. What is the Chain of Custody?

hain of custody, in legal contexts, is the chronological documentation or paper trail that records the sequence of custody, control, transfer, analysis, and disposition of materials, including physical or electronic evidence

### 35. How would you permanently remove the threat of data falling into the wrong hands?



### 36. What is exfiltration?

Data exfiltration occurs when malware and/or a malicious actor carries out an unauthorized data transfer from a computer. It is also commonly called data extrusion or data exportation. Data exfiltration is also considered a form of data theft.

### 37. How do you protect your home wireless access point?

Change the name of your router from the default. The name of your router (often called the service set identifier or SSID) is likely to be a standard, default ID assigned by the manufacturer. Change the name to something unique that only you know.

Change your router's pre-set password(s). The manufacturer of your wireless router probably assigned it a standard default password that allows you to set up and operate the router, as its “administrator.” Hackers know these default passwords, so change it to something only you know.  The same goes for any default “user” passwords. Use long and complex passwords – think at least 12 characters, with a mix of numbers, symbols, and upper and lower case letters. Visit the company’s website to learn how to change the password.

Turn off any “Remote Management” features. Some routers offer an option to allow remote access to your router’s controls, such as to enable the manufacturer to provide technical support.  Never leave this feature enabled. Hackers can use them to get into your home network.   

Log out as Administrator: Once you’ve set up your router, log out as administrator, to lessen the risk that someone can piggyback on your session to gain control of your device.

Keep your router up-to-date: To be secure and effective, the software that comes with your router needs occasional updates. Before you set up a new router and periodically thereafter, visit the manufacturer’s website to see if there’s a new version of the software available for download. To make sure you hear about the latest version, register your router with the manufacturer and sign up to get updates.


### 38. If you were going to break into a database-based website, how would you do it?



### 39. What is the CIA triangle?

The CIA Triad is a security model that highlights core data security objectives and serves as a guide for organizations to keep their sensitive data protected from unauthorized access and data exfiltration.

Confidentiality, integrity and availability, also known as the CIA triad, is a model designed to guide policies for information security within an organization. The model is also sometimes referred to as the AIC triad (availability, integrity and confidentiality) to avoid confusion with the Central Intelligence Agency.

### 40. What is the difference between information protection and information assurance?

I then immediately begin thinking about the difference between Information Security (InfoSec) and Information Assurance (IA). Information security is just like any other career field. There are multiple paths you can take within the field, depending on your interest. The skill sets needed to be effective in these two roles can be very different. Now certainly title isn't everything, and one company uses the term security where the other uses assurance. The US government is quite fond of the information assurance moniker. However, within the profession, we are starting to see a marked delineation between Information Security and Information Assurance. This is similar to the split of information security and information privacy.

### 41. How would you lock down a mobile device?



### 42. What is the difference between closed-source and open-source? Which is better?

Closed source software is software that holds the source code safe and encrypted. Meaning, the user can't copy, modify, or delete parts of the code without some type of consequence. It can go from voiding the warranty to even legal repercussions. Open source software is software that does the complete opposite.

### 43. What is your opinion on hacktivist groups such as Anonymous?

Anonymous is a decentralized international activist/hacktivist collective/movement that is widely known for its various cyber attacks against several governments, government institutions and government agencies, corporations, and the Church of Scientology.



## [Network Security](##network-security)

### 44. What port does ping work over?

Remember that a ping test uses ICMP, so there are no real ports being used. ICMP basically roofs, or sits on top of, the IP address. Therefore it is not a layer four protocol.

### 45. Do you prefer filtered ports or closed ports on your firewall?

A closed port indicates that no application or service is not listening for connections on that port. A closed port can open up at any time if an application or service is started. A filter port indicates that a firewall, filter, or other network issue is blocking the port.

### 46. How exactly does traceroute/tracert work at the protocol level?

Traceroute (tracert) works by sending a packet to an open UDP port on a destination machine. The router then discards the packet and sends off an ICMP notification packet to the original host with the message that the TTL expired from the router. Traceroute transmits packets with small TTL (Time To Live) values.

### 47. What are Linux’s strengths and weaknesses vs. Windows?

The loading time of Windows 10 is much less than that of Windows 7. Stability and performance has been greatly improved in Windows 10. Redesigned UI mixes the advantages of Windows 7 & Windows 8 which helps users of Windows 7 or earlier get comfortable to use it. It is safer to use the latest Windows operating system


Pros
Linux is very stable! ...
Linux is less vulnerable to computer malware! ...
Linux typically does not slow down over time! ...
Linux can breathe new life into old computers! ...
With Linux, you have so many choices in a wide variety of distros! ...
With many Linux distros, you have access to free software which numbers in the thousands!


Cons

MANY WINDOWS PROGRAMS WILL NOT RUN IN LINUX.

THERE IS A SMALLER SELECTION OF PERIPHERAL HARDWARE DRIVERS FOR LINUX.

THERE IS A LEARNING CURVE FOR PEOPLE WHO ARE NEW TO LINUX.



### 48. What is a firewall? And provide an example of how a firewall can be bypassed by an outsider to access the corporate network.

A firewall is a network security system (hardware, software, or both) which is used to monitor all incoming and outgoing network traffic. Based on a defined set of advanced security rules, the firewall decides to either allow or block specific traffic.

Use a Web-based Proxy. A proxy is a web server that stands in your place and receives and sends information to web destinations. ...
Use a VPN. ...
Use Remote Access to Your Own PC. ...
Kill the Blocking Service. ...
Use Mobile Data as a Stopgap. ...



### 49. Besides firewalls, what other devices are used to enforce network boundaries?

Beyond perimeter security devices and devices that provide internal security, other devices provide myriad additional services, such as acting as load balancers, proxies, and access points that improve network functionality.



### 50. What is the role of network boundaries in information security?

Boundary protection is the "monitoring and control of communications at the external boundary of an information system to prevent and detect malicious and other unauthorized communication." Protection is achieved through the use of gateways, routers, firewalls, guards, and encrypted tunnels



### 51. What does an intrusion detection system do? How does it do it?

Network intrusion detection systems operate at the network level and monitor traffic from all devices going in and out of the network. NIDS performs analysis on the traffic looking for patterns and abnormal behaviors upon which a warning is sent.



### 52. What is a honeypot? What type of attack does it defend against?

 honeypot is a computer or computer system intended to mimic likely targets of cyberattacks. It can be used to detect attacks or deflect them from a legitimate target. ... You may not have heard of them before, but honeypots have been around for decades. The principle behind them is simple: Don't go looking for attackers.


### 53. What technologies and approaches are used to secure information and services deployed on cloud computing infrastructure?


Secure cloud accounts and create groups. Ensure that the root account is secure. ...

Check for free security upgrades. ...

Restrict infrastructure access via firewalls. ...

Tether the cloud. ...

Replace passwords with keys. ...

Turn on auditing and system monitoring.


### 54. What information security challenges are faced in a cloud computing environment?


Data Breaches. Consequences of a data breach may include: ...

Misconfiguration and Inadequate Change Control. ...

Lack of Cloud Security Architecture and Strategy. ...

Insufficient Identity, Credential, Access and Key Management. ...

Account Hijacking. ...

Insider Threat. ...

Insecure Interfaces and APIs. ...

Weak Control Plane.


### 55. Can you give me an overview of IP multicast?

IP multicast is a method of sending Internet Protocol (IP) datagrams to a group of interested receivers in a single transmission. It is the IP-specific form of multicast and is used for streaming media and other network applications. It uses specially reserved multicast address blocks in IPv4 and IPv6.


### 56. How many bits do you need for a subnet size?

A subnet mask is the representation of the network portion of an address. It is also made up of 32 bits with all the bits that represent the network portion being marked as 1s and the other parts marked as 0s.

https://www.ittsystems.com/introduction-to-subnetting/#:~:text=A subnet mask is the,Class A%3A 255.0.


### 57. What is packet filtering?

Packet filtering is one technique, among many, for implementing security firewalls.”i Packet filtering is both a tool and a technique that is a basic building block of network security. ... Windows NT and Windows 2000 support packet filtering. Virtually all commercial firewalls support packet filtering.




### 58. Can you explain the difference between a packet filtering firewall and an application layer firewall?

The application layer firewall takes into consideration the nature of the applications being run (the type, timing of the network connection requests, the type and nature of the traffic generated) whereas the packet filtering firewall simply looks at the packets as they are transferred.


### 59. What are the layers of the OSI model?

In the OSI reference model, the communications between a computing system are split into seven different abstraction layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application.



### 60. How would you login to Active Directory from a Linux or Mac box?

There are several ways that organizations can connect their Linux devices to Active Directory. The easiest is by using LDAP via the PAM module. Organizations can also use Kerberos under this model.


### 61. What is an easy way to configure a network to allow only a single computer to login on a particular jack?

Sticky ports are one of the network admin’s best friends and worst headaches. They allow you to set up your network so that each port on a switch only permits one (or a number that you specify) computer to connect on that port by locking it to a particular MAC address. If any other computer plugs into that port, the port shuts down and you receive a call that they can’t connect anymore. If you were the one that originally ran all the network connections then this isn’t a big issue, and likewise if it is a predictable pattern then it also isn’t an issue. However if you’re working in a hand-me-down network where chaos is the norm then you might end up spending a while toning out exactly what they are connecting to.


### 62. What are the three ways to authenticate a person?

Something you have e.g. Credit Card, ID Card, etc.

Something you know e.g. Password, PIN, etc.

Something you are e.g. Static Biometrics, Fingerprints, etc.

Something you do e.g. Dynamic Biometrics, Voice, etc.


### 63. You find out that there is an active problem on your network. You can fix it, but it is out of your jurisdiction. What do you do?


While the first impulse may be to immediately fix the problem, you need to go through the proper channels. Things may be as they are for a reason. Use e-mail to notify the person in charge of that department, expressing your concerns, and asking for clarification. Make sure your boss is CC’ed into the email chain, and make sure that you save a copy for yourself, in case you need to refer to it later.


### 64. How would you compromise an “office workstation” at a hotel?

Considering how infected these typically are, I wouldn’t touch one with a 10ft pole. That being said, a USB keylogger is easy to fit into the back of these systems without much notice while an autorun program would be able to run quickly and quietly leaving behind software to do the dirty work. In essence, it’s open season on exploits in this type of environment.




### 65. What is worse in firewall detection, a false negative or a false positive? And why?

A false positive is a false alarm. A false negative state is the most serious and dangerous state. This is when the IDS identifies an activity as acceptable when the activity is actually an attack. That is, a false negative is when the IDS fails to catch an attack.


### 66. How would you judge if a remote server is running IIS or Apache?

https://news.netcraft.com


### 67. What is the difference between an HIDS and a NIDS?

IDs examine specific host-based actions, such as what applications are being used, what files are being accessed and what information resides in the kernel logs. NIDs analyze the flow of information between computers, i.e., network traffic. They essentially "sniff" the network for suspicious behavior.


## [Application security](##application-security)

### 68. Describe the last program or script that you wrote. What problem did it solve?


### 69. Can you briefly discuss the role of information security in each phase of the software development lifecycle?



### 70. How would you implement a secure login field on a high traffic website where performance is a consideration?



### 71. What are the various ways to handle account brute forcing?



### 72. What is cross-site request forgery?



### 73. How does one defend against CSRF?



### 74. If you were a site administrator looking for incoming CSRF attacks, what would you look for?



### 75. What’s the difference between HTTP and HTML?



### 76. How does HTTP handle state?



### 77. What exactly is cross-site scripting?



### 78. What’s the difference between stored and reflected XSS?



### 79. What are the common defenses against XSS?



### 80. You are remoted in to a headless system in a remote area. You have no physical access to the hardware and you need to perform an OS installation. What do you do?



### 81. On a Windows network, why is it easier to break into a local account than an AD account?




## [Security architect](##security-architect)

### 82. Explain data leakage and give examples of some of the root causes.



### 83. What are some effective ways to control data leakage?



### 84. Describe the 80/20 rules of networking.



### 85. What are web server vulnerabilities and name a few methods to prevent web server attacks?



### 86. What are the most damaging types of malwares?



### 87. What’s your preferred method of giving remote employees access to the company network and are there any weaknesses associated to it?



### 88. List a couple of tests that you would do to a network to identify security flaws.



### 89. What kind of websites and cloud services would you block?



### 90. What type of security flaw is there in VPN?



### 91. What is a DDoS attack?



### 92. Can you describe the role of security operations in the enterprise?



### 93. What is layered security architecture? Is it a good approach? Why?



### 94. Have you designed security measures that span overlapping information domains? Can you give me a brief overview of the solution?



### 95. How do you ensure that a design anticipates human error?



### 96. How do you ensure that a design achieves regulatory compliance?



### 97. What is capability-based security? Have you incorporated this pattern into your designs? How?



### 98. Can you give me a few examples of security architecture requirements?



### 99. Who typically owns security architecture requirements and what stakeholders contribute?



### 100. What special security challenges does SOA present?



### 101. What security challenges do unified communications present?



### 102. Do you take a different approach to security architecture for a COTS vs a custom solution?



### 103. Have you architected a security solution that involved SaaS components? What challenges did you face?



### 104. Have you worked on a project in which stakeholders choose to accept identified security risks that worried you? How did you handle the situation?



### 105. You see a user logging in as root to perform basic functions. Is this a problem?



### 106. What is data protection in transit vs data protection at rest?



### 107. You need to reset a password-protected BIOS configuration. What do you do?



## [Risk management](##risk-management)


### 108. Is there an acceptable level of risk?

109. How do you measure risk? Can you give an example of a specific metric that measures information security risk?

110. Can you give me an example of risk trade-offs (e.g. risk vs cost)?

111. What is incident management?

112. What is business continuity management? How does it relate to security?

113. What is the primary reason most companies haven’t fixed their vulnerabilities?

114. What’s the goal of information security within an organization?

115. What’s the difference between a threat, vulnerability, and a risk?

116. If you were to start a job as head engineer or CSO at a Fortune 500 company due to the previous guy being fired for incompetence, what would your priorities be? [Imagine you start on day one with no knowledge of the environment]

117. As a corporate information security professional, what’s more important to focus on: threats or vulnerabilities?

118. If I’m on my laptop, here inside my company, and I have just plugged in my network cable. How many packets must leave my NIC in order to complete a traceroute to twitter.com?

119. How would you build the ultimate botnet?

120. What are the primary design flaws in HTTP, and how would you improve it?

121. If you could re-design TCP, what would you fix?

122. What is the one feature you would add to DNS to improve it the most?

123. What is likely to be the primary protocol used for the Internet of Things in 10 years?

124. If you had to get rid of a layer of the OSI model, which would it be?

125. What is residual risk?

126. What is the difference between a vulnerability and an exploit?


## [Security audits and incident response](##security-audits-and-incident-response)

127. What is an IT security audit?

128. What is an RFC?

129. What type of systems should be audited?

130. Have you worked in a virtualized environment?

131. What is the most difficult part of auditing for you?

132. Describe the most difficult auditing procedure you’ve implemented.

133. What is change management?

134. What types of RFC or change management software have you used?

135. What do you do if a rollout goes wrong?

136. How do you manage system major incidents?

137. How do you ask developers to document changes?

138. How do you compare files that might have changed since the last time you looked at them?

139. Name a few types of security breaches.

140. What is a common method of disrupting enterprise systems?

141. What are some security software tools you can use to monitor the network?

142. What should you do after you suspect a network has been hacked?

143. How can you encrypt email to secure transmissions about the company?

144. What document describes steps to bring up a network that’s had a major outage?

145. How can you ensure backups are secure?

146. What is one way to do a cross-script hack?

147. How can you avoid cross script hacks?

148. How do you test information security?

149. What is the difference between black box and white box penetration testing?

150. What is a vulnerability scan?

151. In pen testing what’s better, a red team or a blue team?

152. Why would you bring in an outside contractor to perform a penetration test?

## [Cryptography](##cryptography)

153. What is secret-key cryptography?

154. What is public-key cryptography?

155. What is a session key?

156. What is RSA?

157. How fast is RSA?

158. What would it take to break RSA?

159. Are strong primes necessary for RSA?

160. How large a module (key) should be used in RSA?

161. How large should the primes be?

162. How is RSA used for authentication in practice? What are RSA digital signatures?

163. What are the alternatives to RSA?

164. Is RSA currently in use today?

165. What are DSS and DSA?

166. What is difference between DSA and RSA?

167. Is DSA secure?

168. What are special signature schemes?

169. What is a blind signature scheme?

170. What is a designated confirmer signatures?

171. What is a fail-stop signature scheme?

172. What is a group signature?

173. What is blowfish?

174. What is SAFER?

175. What is FEAL?

176. What is Shipjack?

177. What is stream cipher?

178. What is the advantage of public-key cryptography over secret-key cryptography?

179. What is the advantage of secret-key cryptography over public-key cryptography?

180. What is Message Authentication Code (MAC)?

181. What is a block cipher?

182. What are different block cipher modes of operation?

183. What is a stream cipher? Name a most widely used stream cipher.

184. What is one-way hash function?

185. What is collision when we talk about hash functions?

186. What are the applications of a hash function?

187. What is trapdoor function?

188. Cryptographically speaking, what is the main method of building a shared secret over a public medium?

189. What’s the difference between Diffie-Hellman and RSA?

190. What kind of attack is a standard Diffie-Hellman exchange vulnerable to?

191. What’s the difference between encoding, encryption, and hashing?

192. In public-key cryptography you have a public and a private key, and you often perform both encryption and signing functions. Which key is used for which function?

193. What’s the difference between Symmetric and Asymmetric encryption?

194. If you had to both encrypt and compress data during transmission, which would you do first, and why?

195. What is SSL and why is it not enough when it comes to encryption?

196. What is salting, and why is it used?

197. What are salted hashes?

198. What is the Three-way handshake? How can it be used to create a DOS attack?

199. What’s more secure, SSL or HTTPS?

200. Can you describe rainbow tables?


