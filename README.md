# Cybersecurity-Roadmap


## Index

1. [Linux](#1-linux-operating-system)
2. [Computer Networks](#2-networkingosi)
3. [Security Features and Vulnerabilities](#3-security-features-and-vulnerabilities)
4. [Encryption, Authentication, and Access Control](#4-encryption-authentication-and-access-control)
5. [Metasploit and Wireshark](#5-metasploit-and-wireshark)
6. >Encryption (Anonsurf) and more
7. [SQL Injection and XSS](#6-sql-injection-and-xss)
8. >Free Courses and Certifications
9. >Controlled Simulation Labs to try pentesting

---

### Note
>SCREENSHOTS INFORMATION


### 1. Linux Operating System

- The operating system Linux is one of the widely used operating system, community-developed operating system (OS) for computers, servers, mainframes, mobile devices and embedded devices. It is supported on almost every major computer platform, including x86, ARM and SPARC, making it one of the most widely supported operating systems.

- **Resources**
  - [Video Resource: Introduction to Linux & Terminal Commands by Kunal Kushwaha](https://m.youtube.com/watch?v=iwolPf6kN-k&t=3530s)
  - [Linux Commands Cheat Sheet by Linux Training Academy](https://www.linuxtrainingacademy.com/linux-commands-cheat-sheet/)
  - >Resource for apache servers, postGRE, proxies
  - >Making scripts and saving in /usr/ and path

- **Tasks:**
  - Upload a report about your Linux System, including device specification, network information, and drivers using the Terminal
  - Commands for file management and implement a few commands from the shared resources on an application based task of your choice.
  - >More Tasks

### 2. Networking/OSI

- The working of Computer Networks can be simply defined as rules or protocols which help in sending and receiving data via the links which allow Computer networks to communicate. Each device has an IP Address, that helps in identifying a device.

- **Resources**
  - [Video resource by Dion Training](https://www.youtube.com/watch?v=QcS0ElIztHE)
  - [Blog by Karthikeyan Natarajan on Medium](https://medium.com/@cryptushack/quick-intro-to-open-systems-interconnection-osi-model-8cfe2cec7ae3) 

-**Materials extra to explore**
 - [TCP and UDP protocols](https://www.freecodecamp.org/news/tag/computer-networking/)
 - [Configure your network in kali machine and learn about them](https://www.techtarget.com/searchsecurity/feature/How-to-configure-and-customize-Kali-Linux)

- **Tasks:**
  - Upload a report showcasing your usage of Wireshark, capture a few HTTP files and analyse them.
  - See how GET/Request Parameters are processed in insecure communications.
  - In the same report mention some of the networking commands you have read.

### 3. Security Features and Vulnerabilities

- The security measures and techniques used in order to prevent any kind of cyber attacks are the security featurs of that perticular system or sofware. A critical security feature of any technology is the ability to turn it off, undo it, deactivate it, or otherwise separate the harm it might cause from those it might harm.
[Click here for the content](https://portswigger.net/blog)

**Tasks:**
<ol>
  <li>Understand the overview and concept</li>
  <li>Try to find out the tools used for these purposes</li>
  <li>Make a list of the tools and solve access control labs using burpsuite (atleast 2)</li>
</ol>
### 4. Encryption, Authentication, and Access Control.

- Encryption is the process by which a readable message is converted to an unreadable form to prevent unauthorized parties from reading it. Decryption is the process of converting an encrypted message back to its original (readable) format. The original message is called the plaintext message.
- authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to. Authentication collects information from the user or entity in the form of text (e.g., passwords), unstructured data (e.g., image of the user's face), or an access token. Authorization requires a token proving that the entity is authenticated and additional information about the entity to apply access rules
1. [Access-Control](https://www.prplbx.com/resources/blog/broken-access-control/)
2. [Authentication](https://auth0.com/blog/what-is-broken-authentication/)
3. [Encryption/Decryption](https://portswigger.net/blog/breaking-encrypted-data-using-burp)

**Tasks:**
<ol>
  <li>Try to use Burpsuite and learn how different tools can be used for this purpose</li>
  <li>Learn the commands</li>
</ol>
**labs to solve**
- [lab 1](https://portswigger.net/web-security/access-control/lab-unprotected-admin-functionality-with-unpredictable-url)
- [lab 2](https://portswigger.net/web-security/access-control/lab-user-id-controlled-by-request-parameter/)

### 5. Metasploit and Wireshark

- Metasploit is the world’s leading open-source penetrating framework used by security engineers as a penetration testing system and a development platform that allows to create security tools and exploits. The framework makes hacking simple for both attackers and defenders.
- Wireshark is a software tool used to monitor the network traffic through a network interface. It is the most widely used network monitoring tool today. Wireshark is loved equally by system administrators, network engineers, network enthusiasts, network security professionals and black hat hackers. 
The extent of its popularity is such, that experience with Wireshark is considered as a valuable/essential trait in a computer networking-related professional.

1. [click here for the video of penetration using metasploit and wireshark](https://www.youtube.com/watch?v=kdTKHMkDcgs)

**Tasks:**
<ol>
  <li>Watch the video and make a note of the steps</li>
  <li>Learn the commands</li>
</ol>

### 6. SQL Injection and XSS

- SQL injection, also known as SQLI, is a common attack vector that uses malicious SQL code for backend database manipulation to access information that was not intended to be displayed. This information may include any number of items, including sensitive company data, user lists or private customer details.
- Cross-site scripting (XSS) is an attack in which an attacker injects malicious executable scripts into the code of a trusted application or website. Attackers often initiate an XSS attack by sending a malicious link to a user and enticing the user to click it.
1. [click here for the video](https://www.youtube.com/watch?v=cx6Xs3F_1Uc)
2. [click here for more information](https://www.w3schools.com/sql/sql_injection.asp)

**Tasks:**
<ol>
  <li>Watch the video and make a note of the steps</li>
  <li>Learn the commands</li>
  <li>Solve the burpsuite XSS and SQL injection labs</li>
</ol>



## Submissions
1. Fork this repo
2. Fetch changes
3. Make changes, upload your tasks completed according to the tasks mentioned, in PDF, or script format
4. Make a pull request with relevant commit message
