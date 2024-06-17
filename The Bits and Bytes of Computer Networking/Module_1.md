# The TCP/IP Five-Layer Network Model
![image](https://github.com/jerrinmg/Goolge_Course/assets/166682032/c3fc8fe1-8741-459c-b128-b7e2de11d49d)


Difference between TCP Model (4 ) and 5 Layer Module Link Layer is split into Data link Layer and Physical Layer in 5 layer model. 
Difference between 5 Layer Module Link Layer and OSI Model = Application layer split into : Presentation Layer and Session layer in addition to the physical layer.
OSI = The Open Systems Interconnection (OSI) model is a reference model from the International Organization for Standardization.

 comparison of the OSI model, TCP/IP model, and the Five-Layer model, including details about their date of introduction and popularity, presented in a table format:

| **Feature**                      | **OSI Model**                            | **TCP/IP Model**                            | **Five-Layer Model**                      |
|----------------------------------|------------------------------------------|--------------------------------------------|------------------------------------------|
| **Date of Introduction**         | 1984                                     | 1970s                                      | 1980s                                    |
| **Layers**                       | 7                                        | 4 (sometimes viewed as 5)                  | 5                                        |
| **Layers Detail**                | Application                              | Application                                | Application                              |
|                                  | Presentation                             | Transport                                  | Transport                                |
|                                  | Session                                  | Internet                                   | Network                                  |
|                                  | Transport                                | Link                                       | Data link                                |
|                                  | Network                                  |                                            | Physical                                 |
|                                  | Data link                                |                                            |                                          |
|                                  | Physical                                 |                                            |                                          |
| **Usage**                        | Theoretical framework for network design | Practical framework for internet and WANs  | Practical framework for education and simpler network design |
| **Popularity**                   | Widely taught and referenced, less used  | Most widely used for internet protocols    | Used in educational contexts and simpler implementations |
| **Main Use Cases**               | Network design, education, and troubleshooting| Real-world networking, internet, and protocol implementation | Education, simplified network implementations |


The analogy will use the postal service throughout, and the real-life example will detail how an email travels through the network. 

### OSI Model Explained with Postal Analogy and Real-Life Example (Email)

#### 1. Application Layer
- **Postal Analogy:** You write a letter.
- **Real-Life Example:** You compose an email using an email client like Outlook or Gmail.
- **Details:**
  - **Protocols:** SMTP (Simple Mail Transfer Protocol) for sending email, POP3/IMAP for receiving email.
  - **Action:** The email client encodes your message and attachments into a standardized format, such as ASCII for text and base64 for attachments.

#### 2. Presentation Layer
- **Postal Analogy:** You translate the letter into a language the recipient understands and ensure the format is appropriate.
- **Real-Life Example:** The email client translates your email into a format that the recipient's email client can understand.
- **Details:**
  - **Protocols:** MIME (Multipurpose Internet Mail Extensions) for attachments and format conversions.
  - **Action:** The email client might encrypt the message for security or compress it to save bandwidth.

#### 3. Session Layer
- **Postal Analogy:** You decide to start a conversation and agree on the rules of the conversation with your recipient.
- **Real-Life Example:** The email client establishes a session with the mail server to send the email.
- **Details:**
  - **Protocols:** SMTP for establishing sessions.
  - **Action:** The session layer manages the login credentials and maintains the connection until the email is sent.

#### 4. Transport Layer
- **Postal Analogy:** You package the letter in an envelope and ensure it has a return address.
- **Real-Life Example:** The email client ensures the email is broken down into packets and provides error-checking to ensure all packets arrive correctly.
- **Details:**
  - **Protocols:** TCP (Transmission Control Protocol) for reliable delivery.
  - **Action:** TCP segments the email into smaller packets, adds sequence numbers, and ensures error correction.

#### 5. Network Layer
- **Postal Analogy:** The postal service determines the best route to deliver the letter.
- **Real-Life Example:** The network layer determines the path your email packets will take across the internet to reach the recipient's mail server.
- **Details:**
  - **Protocols:** IP (Internet Protocol).
  - **Action:** IP addresses are added to each packet, and routers determine the best path through the network.

#### 6. Data Link Layer
- **Postal Analogy:** The letter is handled by local postal workers who ensure it reaches the correct neighborhood or post office.
- **Real-Life Example:** The data link layer handles the physical addressing and ensures packets are delivered to the correct device on the local network.
- **Details:**
  - **Protocols:** Ethernet for wired networks, Wi-Fi for wireless networks.
  - **Action:** MAC (Media Access Control) addresses are used to deliver the packets to the correct device within the local network, handling error detection and frame synchronization.

#### 7. Physical Layer
- **Postal Analogy:** The physical transportation of the letter by postal trucks, planes, or bicycles.
- **Real-Life Example:** The actual transmission of bits over the physical medium (cables, radio waves).
- **Details:**
  - **Protocols:** Various physical media standards like CAT5 cables for Ethernet or 802.11 for Wi-Fi.
  - **Action:** Electrical signals, light pulses, or radio waves carry the bits that make up your email over the network infrastructure.

### Differences Between Network and Data Link Layers

**Network Layer (Layer 3):**
- **Function:** Handles the logical addressing and routing of packets across different networks.
- **Protocols:** IP (Internet Protocol), ICMP (Internet Control Message Protocol).
- **Example:** Deciding the best route for packets to travel from the sender's network to the recipient's network using IP addresses.
- **Analogy:** The postal service determining the best route to deliver the letter across cities and states.

**Data Link Layer (Layer 2):**
- **Function:** Handles the physical addressing and reliable data transfer between devices on the same network.
- **Protocols:** Ethernet, Wi-Fi (IEEE 802.11), ARP (Address Resolution Protocol).
- **Example:** Delivering packets within the same local area network (LAN) using MAC addresses.
- **Analogy:** Local postal workers ensuring the letter reaches the correct neighborhood or post office within the city.


===================================================<br />

Here is a summary that includes the comparisons used to explain each layer:

The passage explains the five layers of a networking model and uses comparisons to describe the role of each layer:

1. Physical Layer - Represents the physical networking hardware like cables, connectors, and specifications for sending signals. Compared to the delivery truck and roads.

2. Data Link Layer - Defines protocols like Ethernet for interpreting signals so devices on the same network can communicate. Compared to how delivery trucks get from one intersection to the next.

3. Network Layer - Allows different networks to communicate with each other through devices known as routers using protocols like IP. Compared to identifying which roads to take from address A to B. 

4. Transport Layer - Handles communication between specific applications using protocols like TCP (reliable) and UDP (unreliable). Compared to the delivery driver knocking on your door when the package arrives.

5. Application Layer - Includes protocols users directly interact with like web browsers and email. Compared to the contents of the delivered package itself.

The layers are visualized as different aspects of a package being delivered to help understand how network communication works from the physical components up to the user applications.<br />
![image](https://github.com/jerrinmg/Goolge_Course/assets/166682032/ac9b127a-8d46-4abb-9416-925680ce375c)

==============================================<br />


## A. Introduction to Defensive Security

1.Blue Team: ![image](https://github.com/jerrinmg/30day/assets/166682032/e300349c-c617-423e-b84a-02c62edf8e9f)

## 2. Some tasks of the Blue Team

### a. User Cyber Security Awareness

* Trainings users about cyber security

### b. Documenting and Managing Assets

* Know what you have

### c. Updating and Patching Systems

* Updated and patched against any known vulnerability

### d. Setting up Preventative Security Devices

* Firewall and intrusion prevention systems (IPS)

### e. Setting up Logging and Monitoring Devices

* Without monitoring, how can you detect malicious activities?
  

**Defensive Security: SOC, Threat Intelligence DFIR**

=====================================<br />

### Security Operations Center (SOC)

* Monitors network and systems to detect malicious cyber security events
* Areas of interest:
	+ Vulnerabilities
	+ Policy violations
	+ Unauthorized activity
	+ Network intrusions


### Threat Intelligence

* Aims to gather information to help companies prepare against potential adversaries
* Involves collecting, processing, and analyzing data to identify threats and predict attacks
* Enables threat-informed defense and mitigation of attacks

### Digital Forensics and Incident Response (DFIR)

* **Digital Forensics**:
	+ Analyzing evidence of an attack and its perpetrators
	+ Focus areas: file system, system memory, system logs, network logs
* **Incident Response**:
	+ Methodology for handling cyber attacks and data breaches
	+ Four phases: preparation, detection and analysis, containment and recovery, post-incident activity![image](https://github.com/jerrinmg/30day/assets/166682032/f17ba3c5-d3e6-4bd7-a542-5481b5c19fc7)

* **Malware Analysis**:
	+ Learning about malicious software (malware) to understand its behavior and impact
	+ Types of malware: virus, Trojan horse, ransomware
	+ Analysis techniques: static analysis, dynamic analysis

