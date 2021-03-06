Please read CONTRIBUTING.md to contribute

# Content

- [General](#general)
- [Network Security](#network-security)
- [Application security](#application-security)
- [Security architect](#security-architect)
- [Risk management](#risk-management)
- [Security audits and incident response](#security-audits-and-incident-response)
- [Cryptography](#cryptography)




---------------------------

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

As the login field is a parameter that the server receives from the user, we make sure to use input validation to avoid attackers like SQL Injection or XSS.

Input validation is a best practice which by chance may help defend against these attacks, but ultimately you should be using prepared statement/parameterised queries for SQL to prevent SQL injection and encode/escape user input to prevent XSS.

### 71. What are the various ways to handle account brute forcing?

Account Lockouts After Failed Attempts. ...

Make the Root User Inaccessible via SSH. ...

Modify the Default Port. ...

Use CAPTCHA. ...

Limit Logins to a Specified IP Address or Range. ...

Employ 2-Factor Authentication (2FA) ...

Use Unique Login URLs. ...

Monitor Your Server Logs.


### 72. What is cross-site request forgery?

ross-site request forgery, also known as one-click attack or session riding and abbreviated as CSRF or XSRF, is a type of malicious exploit of a website where unauthorized commands are submitted from a user that the web application trusts.


### 73. How does one defend against CSRF?

Websites consist of a combination of client-side and server-side code. The client-side code is HTML and JavaScript that is rendered by and executed in the browser. This allows users to navigate to other URLs on your site, submit HTML forms to the server, and trigger AJAX requests via JavaScript. Your server-side code will intercept the data sent in the HTTP request, and act upon it appropriately.

These server-side actions can also be triggered by forged HTTP requests, unless you explicitly put in protective measures. A CSRF attack occurs when a malicious actor tricks a victim into clicking on a link, or running some code, that triggers a forged request. (This malicious code is typically hosted on a website owned by the attacker, on another domain – hence the “cross-domain” denomination.)

Protecting against CSRF (commonly pronounced “sea-surf”) requires two things: ensuring that GET requests are side-effect free, and ensuring that non-GET requests can only be originated from your client-side code.

### 74. If you were a site administrator looking for incoming CSRF attacks, what would you look for?

Normally, you wouldn't know if the incoming request is a CSRF attack or not because in both cases they would look the same except that the CSRF is sent without the user's consent. BUT if your page contains somekind of a "challenge", like a gotcha for instance, then you would be sure that the user himself/herself made the request "knowingly".

### 75. What’s the difference between HTTP and HTML?

HTML is a Language while HTTP is a Protocol. ... On the contrary, HTTP (Hypertext Transfer Protocol) is a protocol for transferring the hypertext pages from Web Server to Web Browser. For exchanging web pages between Server and Browser, an HTTP session is setup using protocol methods (e.g. GET, POST etc.).

### 76. How does HTTP handle state?

HTTP is called as a stateless protocol because each request is executed independently, without any knowledge of the requests that were executed before it, which means once the transaction ends the connection between the browser and the server is also lost.

### 77. What exactly is cross-site scripting?

Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted websites. XSS attacks occur when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a different end user.

### 78. What’s the difference between stored and reflected XSS?

Stored XSS, also known as persistent XSS, is the more damaging of the two. It occurs when a malicious script is injected directly into a vulnerable web application. Reflected XSS involves the reflecting of a malicious script off of a web application, onto a user's browser.

### 79. What are the common defenses against XSS?

Specifying a charset. First of all, ensure that your web page specifies the UTF-8 charset in the headers or in the very beginning of the head element HTML encode all inputs to prevent a UTF-7 attack in Internet Explorer (and older versions of Firefox) despite other efforts to prevent XSS.

HTML escaping. Keep in mind that you need to HTML-escape all user input. This includes replacing < with &lt;, > with &gt;, & with &amp; and " with &quot;. If you will ever use single-quoted HTML attributes, you need to replace ' with &#39; as well. Typical server-side scripting languages such as PHP provide functions to do this, and I encourage you to expand on these by creating standard functions to insert HTML elements rather than inserting them in an ad-hoc manner.

Other types of escaping. You still, however, need to be careful to never insert user input as an unquoted attribute or an attribute interpreted as JavaScript (e.g. onload or onmouseover). Obviously, this also applies to script elements unless the input is properly JavaScript-escaped, which is different from HTML escaping. Another special type of escaping is URL escaping for URL parameters (do it before the HTML escaping to properly include a parameter in a link).

Validating URLs and CSS values. The same goes for URLs of links and images (without validating based on approved prefixes) because of the javascript: URL scheme, and also CSS stylesheet URLs and data within style attributes. (Internet Explorer allows inserting JavaScript expressions as CSS values, and Firefox is similarly problematic with its XBL support.) If you must include a CSS value from an untrusted source, you should safely and strictly validate or CSS escape it.

Not allowing user-provided HTML. Do not allow user-provided HTML if you have the option. That is an easy way to end up with an XSS problem, and so is writing a "parser" for your own markup language based on simple regex substitutions. I would only allow formatted text if the HTML output were generated in an obviously safe manner by a real parser that escapes any text from the input using the standard escaping functions and individually builds the HTML elements. If you have no choice over the matter, use a validator/sanitizer such as AntiSamy.

Preventing DOM-based XSS. Do not include user input in JavaScript-generated HTML code and insert it into the document. Instead, use the proper DOM methods to ensure that it is processed as text, not HTML.


### 80. You are remoted in to a headless system in a remote area. You have no physical access to the hardware and you need to perform an OS installation. What do you do?

There are a couple of different ways to do this, but the most like scenario you will run into is this: What you would want to do is setup a network-based installer capable of network-booting via PXE (if you’ve ever seen this during your system boot and wondering what it was for, tada). Environments that have very large numbers of systems more often than not have the capability of pushing out images via the network. This reduces the amount of hands-on time that is required on each system, and keeps the installs more consistent.

### 81. On a Windows network, why is it easier to break into a local account than an AD account?

Windows local accounts have a great deal of baggage tied to them, running back a long long way to keep compatibility for user accounts. If you are a user of passwords longer than 13 characters, you may have seen the message referring to this fact. However, Active Directory accounts have a great deal of security tied onto them, not the least of which is that the system actually doing the authenticating is not the one you are usually sitting at when you are a regular user. Breaking into a Windows system if you have physical access is actually not that difficult at all, as there are quite a few dedicated utilities for just such a purpose, however that is beyond the scope of what we’ll be getting into here.


## [Security architect](##security-architect)

### 82. Explain data leakage and give examples of some of the root causes.

Data leakage is the unauthorized transmission of data from within an organization to an external destination or recipient. The term can be used to describe data that is transferred electronically or physically. Data leakage threats usually occur via the web and email, but can also occur via mobile data storage devices such as optical media, USB keys, and laptops.

### 83. What are some effective ways to control data leakage?

Applying a Policy of Least Privilege (POLP) to Data Access. It’s hard for someone to accidentally leak data they don’t have access to it. A policy of least privilege restricts each user’s data access to the absolute minimum they need to perform their job function. Using such a policy also helps to minimize the risk of intentional data leaks, too.

Place Restrictions on What Email Domains Employees Can Send Attachments to on Company Systems. Some email clients and applications allow you to organize people into groups or organizations and manage out-of-group communications to some extent. For example, Google Drive can be set to generate a confirmation screen/warning when sharing access to a file with someone outside the employee’s organization/group. Using these kinds of alerts can make it much less likely that data will be accidentally shared.

Establish a BYOD Policy and Enforce It! A bring your own device (BYOD) policy can help your organization define the rules for if and how employees may use personal devices, such as smartphones, laptops, USB drives, and other devices that can be used to copy, store, and transmit data in the workplace. If such devices are not allowed (or have their use restricted) in the workplace, it can reduce the risk of accidental data leakage.

Provide Cybersecurity Awareness Training. Employees need to know not only what the biggest data leak risks are, but what the potential impacts of such leaks can be for the organization. Providing such awareness training helps employees avoid making basic mistakes that lead to data leaks. Additionally, it can help employees identify phishing attempts and other strategies that malicious actors may try to use to steal data.

Installing Basic Cybersecurity Protections on All Network Endpoints. A basic antivirus program or firewall might not stop a determined attacker or a malicious insider, but such basic protections can prevent less sophisticated attempts to steal data from succeeding or at least slow an attacker’s progress. Also, email client antivirus systems can help prevent some data leaks by scanning email attachments for malware.

Making Sure to Clear Sensitive Data from Non-Critical Systems. Does a copy of your company’s most sensitive information, such as customer records and payment card information, need to be on every terminal in the office? No, nor should they be. Cleaning up individual terminals and making sure that all of your most sensitive data is kept on your most isolated (and well-protected) systems is a core part of preventing data leaks. If an attacker gets malware on one random workstation, keeping that workstation clear of sensitive info can lower your risk of a data leak.

Using Defense in Depth Security Strategies. The more layers of protection you can put on your network, the better. Having a layered defense on your network—one that employs firewalls that isolate each asset and restrict peer-to-peer traffic—makes it harder for an attack to access all of your most protected assets at once. This way, even if an attack gets past your outermost perimeter defenses, it will take time and effort for the attacker to access more than a handful of your IT assets.

Install IDS/IPS Systems and Run Penetration Tests. A key part of preventing a data leak is being able to quickly identify an attempt to steal data and contain the breach. The longer it takes to identify an intrusion attempt, the more time an attacker has to breach your defenses and steal data. Intrusion detection systems (IDS) and intrusion prevention systems (IPS) can help with early attack detection and (in the case of IPS) even provide some automated attack prevention. Penetration tests help you test your security measures for potential weaknesses and verify how effective your IDS/IPS solution is at detecting various kinds of intrusion attempts.


### 84. Describe the 80/20 rules of networking.

This rule, often called the Pareto Principle, is defined as such by Investopedia: “[the Pareto Principle] specifies an unequal relationship between inputs and outputs. The principle states that 20 percent of the invested input is responsible for 80 percent of the results obtained. Put another way, 80 percent of consequences stem from 20 percent of the causes.”

In other words, the Pareto Principle is a strategy that attempts to explain how you should delegate your organization’s security resources in order to maximize the security you get. In this case, you are using your assets to protect your network from online threats. However, you might realize that even if you search and search for network vulnerabilities, you won’t find all of them. There are simply too many threats out there to identify. Instead, you use the Pareto Principle to identify where you can do the most good for your organization's network security.

This principle can also work in reverse; only 20 percent of the vulnerabilities on the Internet lead to 80 percent of the data loss. When you think about it, this makes sense. How often do you hear about major data breaches in which multiple vulnerabilities were exploited? Instead, it’s usually just one major hack that led to many compromised accounts.

Yet, the biggest part of effectively using the 80/20 rule is determining what your priorities should be, and which threats are the most dangerous. After all, if everything is a priority, then nothing can get done. This results in all-around subpar security that leaves large threats unchecked.

### 85. What are web server vulnerabilities and name a few methods to prevent web server attacks?

URL Interpretation Attack. ...

SQL Injection attack. ...

Input Validation attack. ...

Buffer Overflow Attacks. ...

Impersonation attacks. ...

Password-based attacks. ...

Denial of Service Attacks.

### 86. What are the most damaging types of malwares?

CIH Virus - 1998.

Melissa Macro Virus/Worm - 1999.

Code Red Worm - 2001.

Slammer Worm - 2003.

SoBig.F Worm – 2003.

MyDoom Worm - 2004.

Conficker Worm 2008.

NotPetya - 2017.

### 87. What’s your preferred method of giving remote employees access to the company network and are there any weaknesses associated to it?

Use strong passwords. ...

Use Two-factor authentication. ...

Update your software. ...

Restrict access using firewalls. ...

Enable Network Level Authentication. ...

Limit users who can log in using Remote Desktop. ...

Set an account lockout policy.


### 88. List a couple of tests that you would do to a network to identify security flaws.

#1) Network Scanning. In this technique, a port scanner is used to identify all the hosts connected to the network. ...

#2) Vulnerability Scanning. ...

#3) Ethical Hacking. ...

#4) Password Cracking. ...

#5) Penetration Testing.

### 89. What kind of websites and cloud services would you block?



### 90. What type of security flaw is there in VPN?

IPSec (Internet Protocol Security):

IPSec furnishes essential authentication, data reliability and encryption services to protect unlawful viewing and data modification. It is limited to sending only IP packets. It uses two security protocols like AH (Authentication Header) and ESP (Encapsulated Security Payload). It applies two forms of modes like transport mode and tunneling mode. Transport mode can merely encrypt the message in data packet while tunneling mode encrypts whole data packet. It is named as a security overlay and is a costly and prolonged activity.

PPTP (Point-to-Point Tunneling Protocol):

It ties in remote client and private server over the internet. It is extensively used protocol and included in window OS. It does not offer encryption and depends on PPP (point-to-point protocol). PPTP is more rapidly and is accessible for Linux and Mac users. Microsoft created it in relationship with other technology companies. Remote users can contact a private network via PPTP with the local ISP dialing. PPTP links with a large network with the help of virtual network for each remote client.

L2TP (Layer 2 Tunneling Protocol):

Microsoft and Cisco have developed L2TP VPN and it relies on PPP (point-to-point protocol) but lacking encryption. It offers data privacy and reliability. L2TP is used as a tunneling protocol to enclose PPP (Point-to-Point Protocol) frames to be sent out over IP, X.25, and Frame Relay or ATM networks. L2TP connections exercise the same verification mechanisms as PPP connections, for instance EAP, CHAP, MS-CHAP, PAP, and SPAP.

SSL VPN:

SSL VPN is a shortened form of Secure Sockets Layer virtual private network that is applied with a usual web browser. It provides remote access to web application, server applications and internal network connections. When data transfer starts between the browser and the SSL VPN, it involves an encryption to protect the data. SSL VPN applies SSL (Secure Sockets Layer) or TLS (Transport Layer Security) technology to encrypt the data. In practice, some SSL VPNs may utilize a self-signed digital certificate that is not usually trusted in the majority web browsers. Therefore, users must use trusted certificate offered by major trusted certificate authorities.


https://doc.lagout.org/network/Common VPN Security Flaws.pdf


### 91. What is a DDoS attack?

A distributed denial-of-service (DDoS) attack is a malicious attempt to disrupt the normal traffic of a targeted server, service or network by overwhelming the target or its surrounding infrastructure with a flood of Internet traffic.

DDoS attacks achieve effectiveness by utilizing multiple compromised computer systems as sources of attack traffic. Exploited machines can include computers and other networked resources such as IoT devices.

### 92. Can you describe the role of security operations in the enterprise?

A Security Operation Center (SOC) is a centralized function within an organization employing people, processes, and technology to continuously monitor and improve an organization's security posture while preventing, detecting, analyzing, and responding to cybersecurity incidents.

### 93. What is layered security architecture? Is it a good approach? Why?

The purpose of a layered security approach is to make sure that every individual defense component has a backup to counter any flaws or gaps in other defenses of security. Individual layers in a multi-layered security approach focuses on a specific area where malware could attack.

### 94. Have you designed security measures that span overlapping information domains? Can you give me a brief overview of the solution?



### 95. How do you ensure that a design anticipates human error?

Apply design features that visibly convey the possibilities for action. Make the options for functional control visible. Errors in planning and action execution can be minimized if controls are visible so that the possibilities and limits for action are known. Provide appropriate feedback.

### 96. How do you ensure that a design achieves regulatory compliance?

Identify applicable Acts, Regulations, Directives, Standards. ...

Identify applicable requirements. ...

Monitor for changes. ...

Determine applicability of changes. ...

Collaborate with your team and subject matter experts. ...

Document your compliance reviews.

### 97. What is capability-based security? Have you incorporated this pattern into your designs? How?

Capability-based security refers to the principle of designing user programs such that they directly share capabilities with each other according to the principle of least privilege, and to the operating system infrastructure necessary to make such transactions efficient and secure.

### 98. Can you give me a few examples of security architecture requirements?

Security Architecture is one component of a products/systems overall architecture and is developed to provide guidance during the design of the product/system. ... These controls serve the purpose to maintain the system's quality attributes such as confidentiality, integrity and availability.

### 99. Who typically owns security architecture requirements and what stakeholders contribute?



### 100. What special security challenges does SOA present?

. Legacy application security
SOA services that wrap legacy applications must take into account the legacy application's security model. Many legacy applications have hardcoded, proprietary security models.

2. Loose coupling of services and applications
SOA security must not violate SOA design principles such as the Loose coupling of services and applications.

3. Services that operate across organizational boundaries
In the past, many organizations have heavily relied on network security to secure applications. However, SOA services often operate across organizational boundaries. It is not enough to simply secure the perimeter with network equipment such as firewalls.

4. Dynamic trust relationships
SOA services are often required to support dynamic trust relationships with partners, customers, and employees.

5. Composite services
The security model must handle scenarios where multiple services work together as a composite service.

6. Diverse mix of old and new technologies
Need to manage security and identity across a range of systems and services.

7. Protection of inflight business data
Data may traverse insecure networks.

8. Need to be compliant with a growing list of standards
SOA is standards oriented. There are a growing list of security SOA related security standards. There is an expectation that SOA security solutions will rely on established standards.

9. SOA flexibility
SOA solutions are intended to flexible and customizable. SOA security models should not restrict flexibility.


### 101. What security challenges do unified communications present?
What is Presence Technology? An integral component of unified communication, presence technology makes collaboration more efficient, allowing users to see the availability status of their colleagues before they connect.


### 102. Do you take a different approach to security architecture for a COTS vs a custom solution?



### 103. Have you architected a security solution that involved SaaS components? What challenges did you face?



### 104. Have you worked on a project in which stakeholders choose to accept identified security risks that worried you? How did you handle the situation?



### 105. You see a user logging in as root to perform basic functions. Is this a problem?

A Linux admin account (root) has many powers that are not permitted for standard users. That being said, it is not always necessary to log all the way off and log back in as root in order to do these tasks. For example, if you have ever used the ‘run as admin’ command in Windows, then you will know the basic concept behind ‘sudo’ or ‘superuser (root) do’ for whatever it is you want it to do. It’s a very simple and elegant method for reducing the amount of time you need to be logged in as a privileged user. The more time a user spends with enhanced permissions, the more likely it is that something is going to go wrong – whether accidentally or intentionally.

### 106. What is data protection in transit vs data protection at rest?

Data protection at rest aims to secure inactive data stored on any device or network. While data at rest is sometimes considered to be less vulnerable than data in transit, attackers often find data at rest a more valuable target than data in motion

### 107. You need to reset a password-protected BIOS configuration. What do you do?

Almost all motherboards use a small coin sized CMOS battery to store all BIOS settings along with the password. To reset the password, unplug the PC, open the cabinet and remove the CMOS battery for approx. 15-30 minutes and then put it back. It'll reset all BIOS settings as well as the password and you'll need to re-enter all settings.

If it fails, then try to remove the battery for at least one hour.

By Using Motherboard Jumper:

Almost all motherboards contain a jumper that can clear all CMOS settings along with the BIOS password. The location of this jumper varies depending upon the motherboard brand. You should read your motherboard manual to check its location. If you don't have the manual then look for the jumpers near the CMOS battery. Most of the manufacturer label the jumper as CLR, CLEAR, CLEAR CMOS, etc.

When you find the jumper, look carefully. There will be 3 pins and the jumper will be joining the center pin to either left or right pin. What you need to do, is remove the jumper and join the center pin to the opposite pin. e.g. if the jumper joins center pin to left pin, then remove it and join center pin to right pin. Now wait for a few seconds and then again remove the jumper and join the center pin to left pin.

Make sure to turn the PC off before opening the cabinet and resetting the jumper.


## [Risk management](##risk-management)


### 108. Is there an acceptable level of risk?

A risk is acceptable when: it falls below an arbi- trary defined probability; it falls below some level that is already tolerated; it falls below an arbitrary defined attributable fraction of total disease burden in the community; the cost of reducing the risk would exceed the costs saved; the cost of reducing the risk ...

### 109. How do you measure risk? Can you give an example of a specific metric that measures information security risk?

Risk = Likelihood of an adverse event X Impact of the adverse event

This usually assumes a time period of a year and calculates the risk due to a single specific cause. When statistically independent multiple causes are considered, the individual risks need to be added to obtain the overall risk. A risk matrix is usually constructed that divides both likelihood and impact values into discrete ranges that can be used to classify applicable causes by the degree of risk they represent - often reducing risk to something as simple as high, medium, and low.

In the equation above, the likelihood of an adverse event is sometimes represented as the product of the probability that an exploitable weakness is present, and the probability that such a weakness is exploited.

If you are going to measure risk, then you will need some type of framework or methodology to use. Risk measurement can have varying degrees of rigor. A few examples to investigate:

Octave - Using OCTAVE, small teams across business units and IT work together to address the security needs of the organization.
FAIR (Factor analysis of information risk) - taxonomy of the factors that contribute to risk and how they affect each other. It is primarily concerned with establishing accurate probabilities for the frequency and magnitude of loss events. It is not, per se, a “cookbook” that describes how to perform an enterprise (or individual) risk assessment.
NIST Risk Management Process - a key component of a holistic, organization-wide risk management process as defined in NIST Special Publication 800-39, Managing Information Security Risk: Organization, Mission, and Information System View. Risk management processes include: (i) framing risk; (ii) assessing risk; (iii) responding to risk; and (iv) monitoring risk.
ISO 27001 Risk Management


### 110. Can you give me an example of risk trade-offs (e.g. risk vs cost)?

A trade-off is an exchange in which one benefit is given up in order to obtain another.

### 111. What is incident management?

Incident management (IcM) is a term describing the activities of an organization to identify, analyze, and correct hazards to prevent a future re-occurrence. If not managed, an incident can escalate into an emergency, crisis or a disaster.

### 112. What is business continuity management? How does it relate to security?

Business continuity management (BCM) is the strategic and tactical capability of the organization to plan and respond to incidents and business disruptions in order to continue business operations at an acceptable, pre-defined level, according to the Business Continuity Institute.

### 113. What is the primary reason most companies haven’t fixed their vulnerabilities?



### 114. What’s the goal of information security within an organization?

Three primary goals of information security are preventing the loss of availability, the loss of integrity, and the loss of confidentiality for systems and data. Most security practices and controls can be traced back to preventing losses in one or more of these areas.


### 115. What’s the difference between a threat, vulnerability, and a risk?

A threat refers to a new or newly discovered incident that has the potential to harm a system or your company overall. There are three main types of threats:

Natural threats, such as floods, hurricanes, or tornadoes
Unintentional threats, like an employee mistakenly accessing the wrong information
Intentional threats, such as spyware, malware, adware companies, or the actions of a disgruntled employee

A vulnerability refers to a known weakness of an asset (resource) that can be exploited by one or more attackers. In other words, it is a known issue that allows an attack to succeed.

Risk is defined as the potential for loss or damage when a threat exploits a vulnerability. Examples of risk include:

Financial losses

Loss of privacy

Damage to your reputation Rep

Legal implications

Even loss of life

Risk can also be defined as:

Risk = Threat x Vulnerability


### 116. If you were to start a job as head engineer or CSO at a Fortune 500 company due to the previous guy being fired for incompetence, what would your priorities be? [Imagine you start on day one with no knowledge of the environment]



### 117. As a corporate information security professional, what’s more important to focus on: threats or vulnerabilities?

Threat – Anything that can exploit a vulnerability, intentionally or accidentally, and obtain, damage, or destroy an asset.

A threat is what we’re trying to protect against.

Vulnerability – Weaknesses or gaps in a security program that can be exploited by threats to gain unauthorized access to an asset.

A vulnerability is a weakness or gap in our protection efforts.

Both are equally important and should be managed to avoid leaking of sensitive corporate information.



### 118. If I’m on my laptop, here inside my company, and I have just plugged in my network cable. How many packets must leave my NIC in order to complete a traceroute to twitter.com?




### 119. How would you build the ultimate botnet?




### 120. What are the primary design flaws in HTTP, and how would you improve it?

HTTP is a difficult one. It was never designed as a universal carrier and it was originally designed as a stateless protocol, so to call out its limitations as such as “design defects” seems a bit harsh.

However, there are a few things that can be legitimately considered defects.

Commands are text-based, which slows down parsing considerably.

It’s point-to-point. This wouldn’t have mattered, but copyright lawyers blocked Squid networks from transparently store-and-forwarding data, which means the protocol has to do the load-balancing.

It’s point-to-point. You can’t receive a multicast stream via HTTP, which is why you have to tolerate awful video, horrible lag and massive delays whilst watching.

URLs break IPv6 standards, which caused an awful mess. As IPv6 was first, that isn’t ok.

URLs cannot support all forms of hypertext. Ted Neilson’s Xanadu uses a hypertext system where you can place elements in any order and recall any version of any page. He basically invented change management systems as well as hypertext. Well, of course, Xanadu still doesn’t really exist, but change management systems do. However, there is no instruction I can place in the URL - other than to access a CGI script - that can handle change management. The order-independence feature (which he created a prototype of under the name of ZigZag) has no parallel at all. HTTP therefore is not a hypertext transport system, but a hypercard transport system minus the trademark infringing name.

HTTP has no means to allow for NEMO (Network Mobility) or truly mobile nodes (ie: no forwarder or mailbox). It’s designed on the assumption that machines are static. Not a terribly good assumption that protocol designers have had to hack their way around.

HTTP is rather poorly maintained as a protocol, which is why a commercially developed replacement (SPDY) is starting to replace it, where we have no meaningful assurances that SPDY is unencumbered and contains no undocumented features that get used by proprietary, closed-source browsers for a fee.


### 121. If you could re-design TCP, what would you fix?

The fundamental flaw within TCP/IP is in its inherent openness, which consequently results in a lack of security. This openness is largely a by-product of the address-defined nature of TCP/IP.

Abstract: QUIC is a new UDP-based transport protocol for the Internet, and specifically, the web. Originally designed and deployed by Google, it already makes up 35% of Google's egress traffic, which corresponds to about 7% of all Internet traffic.


### 122. What is the one feature you would add to DNS to improve it the most?




### 123. What is likely to be the primary protocol used for the Internet of Things in 10 years?

IoT communication protocols are modes of communication that ensure optimum security to the data being exchanged between IoT connected devices. The IoT devices can be connected via an IP network or a non-IP network. Though there is a difference in their range, power, and memory used.


### 124. If you had to get rid of a layer of the OSI model, which would it be?

The Presentation and Session layers from the OSI/ISO model are part of the Application layer in TCP/IP. In other words, in the TCP/IP model, the Application layer is responsible for all the functions that are performed by Presentation and Session layers in the OSI model. You may say that the OSI/ISO model is more detailed.


### 125. What is residual risk?

The residual risk is the amount of risk or danger associated with an action or event remaining after natural or inherent risks have been reduced by risk controls. The general formula to calculate residual risk is where the general concept of risk is or, alternatively.


### 126. What is the difference between a vulnerability and an exploit?

What is the difference between a vulnerability and an exploit? A weakness of a system, process, or architecture that could lead to compromised information or unauthorized access is known as a vulnerability. The act of taking advantage of a vulnerability is known as an exploit.


## [Security audits and incident response](##security-audits-and-incident-response)

### 127. What is an IT security audit?



### 128. What is an RFC?



### 129. What type of systems should be audited?




### 130. Have you worked in a virtualized environment?




### 131. What is the most difficult part of auditing for you?




### 132. Describe the most difficult auditing procedure you’ve implemented.




### 133. What is change management?




### 134. What types of RFC or change management software have you used?




### 135. What do you do if a rollout goes wrong?




### 136. How do you manage system major incidents?




### 137. How do you ask developers to document changes?




### 138. How do you compare files that might have changed since the last time you looked at them?




### 139. Name a few types of security breaches.



#### 1. MAN-IN-THE-MIDDLE ATTACK

A man-in-the-middle (MitM) attack is a difficult security breach to recognize because it involves a bad actor taking advantage of a trusted “man in the middle” to infiltrate your system. Most often, the hacker will start by compromising a customer’s system to launch an attack on your server. Hackers can achieve this by either:

- Sneaking through a connection you’ve already established with your customer
- Stealing a customer’s IP address and disguising themselves as the customer to lure you into providing valuable information or funds

#### 2. DENIAL-OF-SERVICE AND DISTRIBUTED-DENIAL-OF-SERVICE ATTACKS





#### 3. PHISHING AND SPEAR PHISHING

If you’ve ever received an email claiming to be from a trusted company you have an account with—for example, Paypal—but something about the email seemed unusual, then you have probably encountered a phishing attempt. Phishing involves the hacker sending an email designed to look like it has been sent from a trusted company or website. The email will often sound forceful, odd, or feature spelling and grammatical errors. [Phishing emails](https://www.solarwindsmsp.com/products/mail/use-cases/spear-phishing-prevention?promo=blog) will attempt to entice the recipient into performing an action, such as clicking a link or downloading an attachment. The link or attachment usually requests sensitive data or contains malware that compromises the system.

A phishing email is typically sent out to a large number of recipients without a specific target, in the hopes that casting a wide net will result in at least one recipient taking the bait. Spear phishing, on the other hand, has a specific target. With spear phishing, the hacker may have conducted research on the recipient. For example, they might look through an individual’s social media profiles to determine key details like what company the victim works for. The hacker could then use this information to pretend to be the recipient’s employer, giving them a better chance of successfully persuading the victim to share valuable information or even transfer funds. 

#### 4. PASSWORD ATTACK 

According to [Have I Been Pwned](https://haveibeenpwned.com/), a source that allows you to check if your account has been compromised in a data breach, these are the most commonly used passwords:

1. 123456
2. 123456789
3. qwerty
4. password
5. 111111
6. 12345678
7. abc123
8. password1
9. 1234567
10. 12345

On top of being popular, these passwords are also extremely easy for hackers to guess. Sadly, many people and businesses make use of the same passwords for multiple accounts. This means that if the hacker guesses just one of the passwords, they can try that password on other services and get a match. For example, they may get an email and password combination, then try them on bank accounts, looking for a hit. Hackers can use password attacks to compromise accounts, steal your identity, make purchases in your name, and gain access to your bank details. 

Hackers can often guess passwords by using social engineering to trick people or by brute force. To reduce the risk of hackers guessing your passwords, make sure you have a unique password for each of your accounts—and that each of these passwords are complex. They should include a combination of digits, symbols, uppercase letters, and lowercase letters. If possible, it’s best to avoid words found in the dictionary. [Password management tools](https://www.passportalmsp.com/password-management?promo=blog) can generate strong passwords for you and store them in an encrypted vault that can be accessed with a master password and multi-factor authentication so you don’t have to remember them. 

#### 5. EAVESDROP ATTACK

An eavesdrop attack is an attack made by intercepting network traffic. Eavesdropping attacks entail the hacker using your behavior on your network to track things like credit card numbers and other potentially valuable, sensitive information. There are two different types of eavesdrop attacks—active and passive. In an active attack, the hacker will disguise themselves as a trusted server and send queries to the transmitters. A passive attack, on the other hand, listens to information through the transmission network. 

#### 6. CROSS-SITE SCRIPTING ATTACK

A cross-site (XXS) attack attempts to inject malicious scripts into websites or web apps. Launching a successful XXS attack is a reasonably complicated process, which requires the victim to visit a website and have the network translate the website with the attacker’s HTML. This means that when the website reaches the victim’s browser, the website automatically executes the malicious script. The aim of this attack is to capture screenshots, log keystrokes, collect network information, steal cookies, and even remotely access the victim’s device. This can ultimately be one method of launching a larger attack leading to a full-on data breach.

#### 7. MALWARE ATTACK 

A [malware](https://www.solarwindsmsp.com/blog/how-to-remove-malware) attack is an umbrella term that refers to a range of different types of security breaches. This includes the following:

- Polymorphic viruses, which change their signatures frequently to evade signature-based antivirus (AV)
- Systems or boot-record infectors, which are viruses that attach themselves to your hard disk 
- Trojan or trojan horses, which are programs that appear as a typical file like an MP3 download but that hide malicious behavior
- File infectors, which are viruses that attach themselves to code on files
- Macro viruses, which are viruses that target and infect major applications
- Stealth viruses, which take control over your system and then use obfuscation methods like changing the filename to avoid detection
- Worms, which are viruses that propagate across a network
- Logic bombs, which are malicious software programs that are triggered by a specific condition, such as a date and time
- Ransomware, which are malware viruses that block access to the victim’s sensitive data until the victim pays a specific amount of money

Both individuals and businesses can fall victim to these types of attacks, which can have drastic financial, legal, and operational consequences. 





### 140. What is a common method of disrupting enterprise systems?




### 141. What are some security software tools you can use to monitor the network?




### 142. What should you do after you suspect a network has been hacked?




### 143. How can you encrypt email to secure transmissions about the company?




### 144. What document describes steps to bring up a network that’s had a major outage?




### 145. How can you ensure backups are secure?




### 146. What is one way to do a cross-script hack?




### 147. How can you avoid cross script hacks?




### 148. How do you test information security?




### 149. What is the difference between black box and white box penetration testing?




### 150. What is a vulnerability scan?




### 151. In pen testing what’s better, a red team or a blue team?




### 152. Why would you bring in an outside contractor to perform a penetration test?




## [Cryptography](##cryptography)

### 153. What is secret-key cryptography?
Secret-key cryptography is also called symmetric cryptography because the same key is used to both encrypt and decrypt the data. 

- Well-known secret-key cryptographic algorithms include Advanced Encryption Standard (AES), Triple Data Encryption Standard (3DES), and Rivest Cipher 4 (RC4).

### 154. What is public-key cryptography?
Public-key cryptography is also called asymmetric cryptography because different keys are used to encrypt and decrypt the data.

- A well-known public key cryptographic algorithm often used with TLS is the Rivest Shamir Adleman (RSA) algorithm. Another public key algorithm used with TLS that is designed specifically for secret key exchange is the Diffie-Hellman (DH) algorithm. Public-key cryptography requires extensive computations, making it very slow. It is therefore typically used only for encrypting small pieces of data, such as secret keys, rather than for the bulk of encrypted data communications.


### 155. What is a session key?
A session key is any encryption key used to symmetrically encrypt one communication session only. 

- In other words, it's a temporary key that is only used once, during one stretch of time, for encrypting and decrypting data;  future conversations between the two parties would be encrypted with different session keys. 
- A session key is like a password that someone resets every time they log in.


### 156. What is RSA?
RSA (Rivest–Shamir–Adleman) is a public-key cryptosystem that is widely used for secure data transmission. It is also one of the oldest. The acronym RSA comes from the surnames of Ron Rivest, Adi Shamir, and Leonard Adleman, who publicly described the algorithm in 1977.

- In a public-key cryptosystem, the encryption key is public and distinct from the decryption key, which is kept secret (private). An RSA user creates and publishes a public key based on two large prime numbers, along with an auxiliary value. The prime numbers are kept secret. Messages can be encrypted by anyone, via the public key, but can only be decoded by someone who knows the prime numbers

### 157. How fast is RSA?
RSA is a relatively slow algorithm. Because of this, it is not commonly used to directly encrypt user data. More often, RSA is used to transmit shared keys for symmetric key cryptography, which are then used for bulk encryption-decryption.

### 158. What would it take to break RSA?
The security of RSA relies on the practical difficulty of factoring the product of two large prime numbers, the "factoring problem". Breaking RSA encryption is known as the RSA problem. Whether it is as difficult as the factoring problem is an open question.[3] There are no published methods to defeat the system if a large enough key is used.

- In cryptography, the RSA problem summarizes the task of performing an RSA private-key operation given only the public key. The RSA algorithm raises a message to an exponent, modulo a composite number N whose factors are not known. Thus, the task can be neatly described as finding the eth roots of an arbitrary number, modulo N. For large RSA key sizes (in excess of 1024 bits), no efficient method for solving this problem is known; if an efficient method is ever developed, it would threaten the current or eventual security of RSA-based cryptosystems—both for public-key encryption and digital signatures.

### 159. Are strong primes necessary for RSA?
### 160. How large a module (key) should be used in RSA?
### 161. How large should the primes be?
### 162. How is RSA used for authentication in practice? What are RSA digital signatures?
### 163. What are the alternatives to RSA?
### 164. Is RSA currently in use today?


### 165. What are DSS and DSA?
The Digital Signature Standard (DSS) is a Federal Information Processing Standard specifying a suite of algorithms that can be used to generate digital signatures established by the U.S. National Institute of Standards and Technology (NIST) in 1994.

The Digital Signature Algorithm (DSA) is a Federal Information Processing Standard for digital signatures, based on the mathematical concept of modular exponentiation and the discrete logarithm problem. DSA is a variant of the Schnorr and ElGamal signature schemes.
- The DSA algorithm works in the framework of public-key cryptosystems and is based on the algebraic properties of modular exponentiation, together with the discrete logarithm problem, which is considered to be computationally intractable. The algorithm uses a key pair consisting of a public key and a private key. The private key is used to generate a digital signature for a message, and such a signature can be verified by using the signer's corresponding public key. The digital signature provides message authentication (the receiver can verify the origin of the message), integrity (the receiver can verify that the message has not been modified since it was signed) and non-repudiation (the sender cannot falsely claim that they have not signed the message).

### 166. What is difference between DSA and RSA?

Although DSA and RSA have practically the same cryptographic strengths, each have their own advantages when it comes to performance. DSA is faster at decrypting and signing, while RSA is faster at encrypting and verifying.

### 167. Is DSA secure?
A 1024-bit DSA key is not a critical risk. As far as we know, DSA appears to be at least as strong as RSA with the same key size, and in practice a bit stronger. DSA relies on discrete logarithm and the current DL-break record is for 530 bits, while the current record for factorization (RSA) is 768 bits. Best known algorithms for factorization and DL have a lot of similarities, but the final step (where a lot of fast RAM is needed) appears to be more expensive with DL than with factorization. Thus, right now, a 1024-bit DSA key is not a true security risk. Especially since, for signatures, we have less to worry about future break than for encryption; and DSA is signature-only.


### 168. What are special signature schemes?
Since the time Diffie and Hellman introduced the concept of digital signatures (see Question 3), many signature schemes have been proposed in cryptographic literature. These schemes can be categorized as either conventional digital signature schemes (e.g., RSA, DSA) or special signature schemes depending on their security features.

In a conventional signature scheme (the original model defined by Diffie and Hellman), we generally assume the following situation:

The signer knows the contents of the message that he has signed.
Anyone who knows the public key of the signer can verify the correctness of the signature at any time without any consent or input from the signer. (Digital signature schemes with this property are called self-authenticating signature schemes.)
The security of the signature schemes (i.e., hard to forge, non-repudiation, see Question 3) is based on certain complexity-theoretic assumptions.
In some situations, it may be better to relax some of these assumptions, and/or add certain special security features. For example, when Alice asks Bob to sign a certain message, she may not want him to know the contents of the message. In the past decade, a variety of special signature schemes have been developed to fit security needs in different applications.


### 169. What is a blind signature scheme?
Blind signature [27] is a kind of digital signature in which the message is blinded before it is signed. Therefore, the signer will not learn the message content. Then the signed message will be unblinded. At this moment, it is similar to a normal digital signature, and it can be publicly checked against the original message. Blind signature can be implemented using a number of public-key encryption schemes.

### 170. What is a designated confirmer signatures?
Designated confirmer signatures (or sometimes simply “confirmer signatures”) are digital signatures that can be verified only by some help of a semi-trusted designated confirmer. 

### 171. What is a fail-stop signature scheme?
Fail-stop signature (FSS) schemes protect a signer against a forger with unlimited computational power by enabling the signer to provide a proof of forgery, if it occurs. A decade after its invention, there have been several FSS schemes proposed in the literature.


### 172. What is a group signature?
A group signature scheme is a method for allowing a member of a group to anonymously sign a message on behalf of the group. 


### 173. What is blowfish?
Blowfish is a symmetric-key block cipher, designed in 1993 by Bruce Schneier and included in many cipher suites and encryption products. Blowfish provides a good encryption rate in software and no effective cryptanalysis of it has been found to date. However, the Advanced Encryption Standard (AES) now receives more attention, and Schneier recommends Twofish for modern applications.  

Schneier designed Blowfish as a general-purpose algorithm, intended as an alternative to the aging DES and free of the problems and constraints associated with other algorithms. At the time Blowfish was released, many other designs were proprietary, encumbered by patents or were commercial or government secrets. Schneier has stated that, "Blowfish is unpatented, and will remain so in all countries. The algorithm is hereby placed in the public domain, and can be freely used by anyone."


### 174. What is SAFER?
In cryptography, SAFER (Secure And Fast Encryption Routine) is the name of a family of block ciphers designed primarily by James Massey (one of the designers of IDEA) on behalf of Cylink Corporation. The early SAFER K and SAFER SK designs share the same encryption function, but differ in the number of rounds and the key schedule. 



### 175. What is FEAL?
In cryptography, FEAL (the Fast data Encipherment ALgorithm) is a block cipher proposed as an alternative to the Data Encryption Standard (DES), and designed to be much faster in software. The Feistel based algorithm was first published in 1987 by Akihiro Shimizu and Shoji Miyaguchi from NTT. The cipher is susceptible to various forms of cryptanalysis, and has acted as a catalyst in the discovery of differential and linear cryptanalysis.

### 176. What is Shipjack?
Shipjack  is an encryption algorithm for the transmission of information (voice data in particular), developed by the National Security Agency (NSA) in the USA. It uses the Diffie-Hellman key exchange algorithm for the distribution of the cryptographic session keys between peers.

- The Skipjack algorithm was classified as an NSA Type 2 encryption product. It was intended for voice data networks (telephone) and was initially developed for the NSA's ill-fated Clipper Chip project, shown in the image on the right [1]. In 1994, (then) AT&T researcher Matt Blaze, found a serious weakness in the Escrowed Encryption System (EES), which allowed a malicious party to bypass the clipper chip's escrow capability


### 177. What is stream cipher? Name a most widely used stream cipher.

A stream cipher is a symmetric key cipher where plaintext digits are combined with a pseudorandom cipher digit stream (keystream). In a stream cipher, each plaintext digit is encrypted one at a time with the corresponding digit of the keystream, to give a digit of the ciphertext stream. Since encryption of each digit is dependent on the current state of the cipher, it is also known as state cipher. In practice, a digit is typically a bit and the combining operation is an exclusive-or (XOR).

- RC4 - RC4, which stands for Rivest Cipher 4, is the most widely used of all stream ciphers, particularly in software. It's also known as ARCFOUR or ARC4.


### 178. What is the advantage of public-key cryptography over secret-key cryptography?


### 179. What is the advantage of secret-key cryptography over public-key cryptography?


### 180. What is Message Authentication Code (MAC)?
In cryptography, a message authentication code (MAC), sometimes known as a tag, is a short piece of information used to authenticate a message—in other words, to confirm that the message came from the stated sender (its authenticity) and has not been changed. The MAC value protects a message's data integrity, as well as its authenticity, by allowing verifiers (who also possess the secret key) to detect any changes to the message content.


### 181. What is a block cipher?
In cryptography, a block cipher is a deterministic algorithm operating on fixed-length groups of bits, called blocks. It uses an unvarying transformation, that is, it uses a symmetric key. They are specified elementary components in the design of many cryptographic protocols and are widely used to implement the encryption of large amounts of data, including data exchange protocols.  

Even a secure block cipher is suitable for the encryption of only a single block of data at a time, using a fixed key. A multitude of modes of operation have been designed to allow their repeated use in a secure way to achieve the security goals of confidentiality and authenticity. However, block ciphers may also feature as building blocks in other cryptographic protocols, such as universal hash functions and pseudorandom number generators.



### 182. What are different block cipher modes of operation?
In cryptography, a block cipher mode of operation is an algorithm that uses a block cipher to provide information security such as confidentiality or authenticity.[1] A block cipher by itself is only suitable for the secure cryptographic transformation (encryption or decryption) of one fixed-length group of bits called a block.[2] A mode of operation describes how to repeatedly apply a cipher's single-block operation to securely transform amounts of data larger than a block.[3][4][5]  Most modes require a unique binary sequence, often called an initialization vector (IV), for each encryption operation. The IV has to be non-repeating and, for some modes, random as well. The initialization vector is used to ensure distinct ciphertexts are produced even when the same plaintext is encrypted multiple times independently with the same key.[6] Block ciphers may be capable of operating on more than one block size, but during transformation the block size is always fixed. Block cipher modes operate on whole blocks and require that the last part of the data be padded to a full block if it is smaller than the current block size.[2] There are, however, modes that do not require padding because they effectively use a block cipher as a stream cipher.  Historically, encryption modes have been studied extensively in regard to their error propagation properties under various scenarios of data modification. Later development regarded integrity protection as an entirely separate cryptographic goal. Some modern modes of operation combine confidentiality and authenticity in an efficient way, and are known as authenticated encryption modes.[7]


### 183. What is a stream cipher? 


### 184. What is one-way hash function?
A one-way hash function, also known as a message digest, fingerprint or compression function, is a mathematical function which takes a variable-length input string and converts it into a fixed-length binary sequence. Furthermore, a one-way hash function is designed in such a way that it is hard to reverse the process, that is, to find a string that hashes to a given value (hence the name one-way.) A good hash function also makes it hard to find two strings that would produce the same hash value.


### 185. What is collision when we talk about hash functions?
If two separate inputs produce the same hash output, it is called a collision. This collision can then be exploited by any application that compares two hashes together – such as password hashes, file integrity checks, etc.


### 186. What are the applications of a hash function?
A cryptographic hash function (CHF) is a mathematical algorithm that maps data of arbitrary size (often called the "message") to a bit array of a fixed size (the "hash value", "hash", or "message digest"). It is a one-way function, that is, a function which is practically infeasible to invert.[1] Ideally, the only way to find a message that produces a given hash is to attempt a brute-force search of possible inputs to see if they produce a match, or use a rainbow table of matched hashes. Cryptographic hash functions are a basic tool of modern cryptography.[2]

### 187. What is trapdoor function?
A trapdoor function is a function that is easy to compute in one direction, yet difficult to compute in the opposite direction (finding its inverse) without special information, called the "trapdoor". Trapdoor functions are widely used in cryptography.

### 188. Cryptographically speaking, what is the main method of building a shared secret over a public medium?
Diffie–Hellman key exchange (DH) is a method of securely exchanging cryptographic keys over a public channel and was one of the first public-key protocols as originally conceptualized by Ralph Merkle and named after Whitfield Diffie and Martin Hellman. DH is one of the earliest practical examples of public key exchange implemented within the field of cryptography.

Traditionally, secure encrypted communication between two parties required that they first exchange keys by some secure physical channel, such as paper key lists transported by a trusted courier. The Diffie–Hellman key exchange method allows two parties that have no prior knowledge of each other to jointly establish a shared secret key over an insecure channel. This key can then be used to encrypt subsequent communications using a symmetric key cipher.

Diffie–Hellman is used to secure a variety of Internet services. However, research published in October 2015 suggests that the parameters in use for many DH Internet applications at that time are not strong enough to prevent compromise by very well-funded attackers, such as the security services of large governments.

### 189. What’s the difference between Diffie-Hellman and RSA?
The Diffie-Hellman approach has each party generate both a public and private key, but only the public key is shared. Once the client on either end of the transaction has verified the other person’s public key, the exchange can be shared.

Because the Diffie-Hellman Key Exchange doesn’t authenticate either party, a hacker could more easily send spoof messages posing as one of the parties in the transaction. For this reason, the Diffie-Hellman approach requires an additional digital signature component. Both RSA and the Diffie-Hellman Exchange have their merits, with technology professionals commonly choosing one over the other due to their own personal preferences. RSA permits digital signatures, a key differentiator from the Diffie-Hellman approach.

Although both the Diffie-Hellman Key Exchange and RSA are the most popular encryption algorithms, RSA tends to be more popular for securing information on the internet. 


### 190. What kind of attack is a standard Diffie-Hellman exchange vulnerable to?
The Diffie-Hellman key exchange is vulnerable to a man-in-the-middle attack. In this attack, an opponent Carol intercepts Alice's public value and sends her own public value to Bob. When Bob transmits his public value, Carol substitutes it with her own and sends it to Alice. Carol and Alice thus agree on one shared key and Carol and Bob agree on another shared key. After this exchange, Carol simply decrypts any messages sent out by Alice or Bob, and then reads and possibly modifies them before re-encrypting with the appropriate key and transmitting them to the other party. This vulnerability is present because Diffie-Hellman key exchange does not authenticate the participants. Possible solutions include the use of digital signatures and other protocol variants.


### 191. What’s the difference between encoding, encryption, and hashing?
Encoding: Reversible transformation of data format, used to preserve usability of data. Hashing: Is a one-way summary of data, cannot be reversed, used to validate the integrity of data. Encryption: Secure encoding of data used to protect confidentiality of data.

### 192. In public-key cryptography you have a public and a private key, and you often perform both encryption and signing functions. Which key is used for which function?
Unlike symmetric cryptography, public key cryptography uses two different keys - one public and one private. The keys are mathematically related, yet it is computationally infeasible to deduce one from the other. Anyone with the public key can encrypt a message but not decrypt it. Only the person with the private key can decrypt the message.

### 193. What’s the difference between Symmetric and Asymmetric encryption?
Symmetric encryption uses a single key that needs to be shared among the people who need to receive the message while asymmetric encryption uses a pair of public key and a private key to encrypt and decrypt messages when communicating.

### 194. If you had to both encrypt and compress data during transmission, which would you do first, and why?
Compress first. If you encrypt then your data turns into (essentially) a stream of random bits. Random bits are incompressable because compression looks for patterns in the data and a random stream, by definition, has no patterns. Of course it matters.

### 195. What is SSL and why is it not enough when it comes to encryption?
SSL is great, but it is simply not enough. The interception the data packets flowing between visitor and website is only one way internet criminals gain access to sensitive information. If SSL has not been properly implemented, some content on a site may NOT covered by the encryption expected.

### 196. What is salting, and why is it used?
In cryptography, a salt is random data that is used as an additional input to a one-way function that hashes data, a password or passphrase. Salts are used to safeguard passwords in storage. Historically a password was stored in plaintext on a system, but over time, additional safeguards were developed to protect a user's password against being read from the system. A salt is one of those methods.  A new salt is randomly generated for each password. In a typical setting, the salt and the password (or its version after key stretching) are concatenated and processed with a cryptographic hash function, and the output hash value (but not the original password) is stored with the salt in a database. Hashing allows for later authentication without keeping and therefore risking exposure of the plaintext password in the event that the authentication data store is compromised.

### 197. What are salted hashes?

Salting hashes sounds like one of the steps of a hash browns recipe, but in cryptography, the expression refers to adding random data to the input of a hash function to guarantee a unique output, the hash, even when the inputs are the same.


### 198. What is the Three-way handshake? How can it be used to create a DOS attack?
The three-way handshake is initiated when the client system sends a SYN message to the server. The server then receives the message and responds with a SYN-ACK message back to the client. Finally, the client confirms the connection with a final ACK message

### 199. What’s more secure, SSL or HTTPS?
SSL (and it’s more recent form TLS) are ways of encrypting a connection. It’s most well known use is in HTTPS where it is used to encrypt HTTP traffic but it can also encrypt other traffic (e.g. email traffic).

So HTTPS used SSL/TLS. So asking which is more secure doesn’t make sense. One is used to provide the other.

### 200. Can you describe rainbow tables?
A rainbow table is a precomputed table for caching the output of cryptographic hash functions, usually for cracking password hashes. Tables are usually used in recovering a key derivation function (or credit card numbers, etc.) up to a certain length consisting of a limited set of characters. It is a practical example of a space–time tradeoff, using less computer processing time and more storage than a brute-force attack which calculates a hash on every attempt, but more processing time and less storage than a simple key derivation function with one entry per hash. Use of a key derivation that employs a salt makes this attack infeasible.

