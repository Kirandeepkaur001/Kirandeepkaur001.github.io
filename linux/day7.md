# Day 7 :

# Host
A host is any device (like a computer, laptop, mobile, server, etc.) that is connected to a network and can send or receive data.

  ### **_Examples of a Host:_**
  * Your laptop connected to Wi-Fi.
  * A mobile phone using the internet.
  * A website server (like Google or Facebook).
  * A printer connected to your home etwork.

  ### **_Where do Hosts work?_**
  Hosts work in networks, like:
  * Your home Wi-Fi.
  * An office network.
  * The Internet.

  ### **_What can a Host do?_**
  **_Send data_** – like sending an email or uploading a photo.
  **_Receive data_** – like watching a video or opening a website.
  **_Store and share_** – like sharing a file or hosting a website.

  ### **_Why is it called a “Host”?_**
  Just like a host in a party gives you food and space, a network host provides or receives information and services.

  ### **_Important terms related to Host:_**

  | Term           | Meaning in Simple Words                                |
  | -------------- | ------------------------------------------------------ |
  | **IP Address** | Unique number given to each host in a network.         |
  | **Hostname**   | The name of a host (like `my-laptop` or `google.com`). |
  | **Server**     | A special host that gives services (like a website).   |
  | **Client**     | A host that uses the services (like your phone).       |

# Protocol
A protocol is like a set of rules that computers follow to communicate with each other.

  ### **_Example:_**
  * Think of a protocol like a language.
  * If two people speak the same language (like English), they can talk and understand each other.
  * Similarly, two computers use the same protocol to send and receive data properly.

  ### **_Real-life comparison:_**

  | Real Life                 | Computer Network                  |
  | ------------------------- | --------------------------------- |
  | Language (English, Hindi) | Protocol (HTTP, TCP, IP)          |
  | Saying “Hello” first      | Sending a “Request”               |
  | Waiting for a reply       | Waiting for a “Response”          |
  | Rules of a game           | Rules of communication (protocol) |

  ### **_Why Protocols Are Needed?_**
  Without protocols:
  * Computers won’t understand each other.
  * Data will get lost or be misread.
  * Communication will fail.

  ### **_Common Internet Protocols:_**

  | Protocol  | Full Form                     | Used For                                     |
  | --------- | ----------------------------- | -------------------------------------------- |
  | **HTTP**  | HyperText Transfer Protocol   | Opening websites (like Google, YouTube)      |
  | **HTTPS** | Secure HTTP                   | Secure websites (with 🔒 lock symbol)        |
  | **IP**    | Internet Protocol             | Giving addresses to devices (IP address)     |
  | **TCP**   | Transmission Control Protocol | Reliable data transfer (like sending emails) |
  | **FTP**   | File Transfer Protocol        | Sending files between computers              |
  | **SMTP**  | Simple Mail Transfer Protocol | Sending emails                               |

# IP Address
An IP address (Internet Protocol address) is like a home address for a device on a network or the internet.
It helps devices find each other and communicate.

  ### **_Simple Example:_**
      Imagine your house has an address like:
      123 Main Street
      Similarly, your computer or mobile phone on a network has an address like:
      192.168.1.2
      This is its IP address — so data knows where to go.

  ### **_Why is IP Address important?_**
  Without an IP address:
  * Your phone wouldn’t know how to connect to websites.
  * A message wouldn’t know which computer to reach.

  # **_Types of IP Addresses:_**

  ### **_1. Based on Use_**

  | Type           | Meaning in Simple Words                     | Example     |
  | -------------- | ------------------------------------------- | ----------- |
  | **Private IP** | Used **inside your home or office** network | 192.168.1.2 |
  | **Public IP**  | Used **on the internet**, given by your ISP | 103.25.54.1 |

   Example:
  * Your phone at home has a private IP like 192.168.1.4
  * Your Wi-Fi router has a public IP like 103.XXX.XXX.X (seen on the internet)

  ### **_2. Based on Permanence_**

  | Type           | Meaning                           |
  | -------------- | --------------------------------- |
  | **Static IP**  | Stays the **same every time**     |
  | **Dynamic IP** | **Changes** each time you connect |

  Example:
  * Companies use static IPs for servers (so websites are always reachable).
  * Homes use dynamic IPs (automatically given by the ISP).

  ### **_3. Based on Version_**

  | Type     | Full Form                   | Looks Like                     |
  | -------- | --------------------------- | ------------------------------ |
  | **IPv4** | Internet Protocol version 4 | 192.168.0.1                    |
  | **IPv6** | Internet Protocol version 6 | 2001:0db8:85a3::8a2e:0370:7334 |

# Classful Addressing
Classful Addressing is an old method of dividing the IPv4 address space into fixed-size blocks called classes.

# Classes of IP Address 
When the internet was first created, people needed a way to give unique IP addresses to all devices, whether:
* A huge company with millions of computers
* A small business with just 10 computers
  
To make IP addresses easy to manage, they are divided into 5 classes: Class A, B, C, D, and E

These classes help decide:
* How many devices can be in a network
* Whether the IP is used for normal devices, multicasting, or experiments

* **_In IP Address Classes (A, B, C)_**
Each class divides the 32-bit IPv4 address into two parts:

**_Prefix = Network part_**
**_Suffix = Host part_**

Example:
IP: 10.0.0.1
Prefix: 10
Suffix: 0.0.1
---

  ### **_Class A – For Very Big Networks_**
  Used by: Very large companies or government

  Example:
  * Imagine you’re running a big company like Google or Amazon with millions of devices.
  * You need a lot of IP addresses in one network.

    First number of IP is from 1 to 126
    Looks like: 10.0.0.1, 25.45.67.89
    You get:
    1 network
    And 16 million host IPs inside it!
    Subnet Mask: 255.0.0.0 (only first part is network, rest is for devices)
    Think: A = All Big companies

  ### **_Class B – For Medium Networks_**
  Used by: Universities, medium-size companies

  Example:
  * Imagine your university or office has thousands of computers.

    First number: 128 to 191
    Looks like: 172.16.0.1, 150.25.10.5
    You get:
    Around 16,000 networks
    Each network can have 65,000 devices
    Subnet Mask: 255.255.0.0
    Think: B = Big, but not the biggest

  ### **_Class C – For Small Networks_**
  Used by: Small businesses, home networks

  Example:
  * You have a small office with fewer than 250 computers.

    First number: 192 to 223
    Looks like: 192.168.0.1, 203.0.113.5
    You get:
    2 million networks
    Each network can have 254 devices only
    Subnet Mask: 255.255.255.0
    Think: C = Compact / Cottage office

  ### **_Class D – For Multicasting_**
  Used by: Live video streaming, group messaging

  What is Multicasting?
  Sending data to many devices at once (like live video to thousands of users)

    First number: 224 to 239
    Example: 224.0.0.1
    Not used for normal devices like laptops
    Think: D = Drama / Distribution (for many people)

  ### **_Class E – For Experiments_**
  Used by: Research, testing, future use
    
    First number: 240 to 255
    Example: 250.0.0.1
    Not used for normal internet
    Think: E = Experiment

  #  **_Full Table to Remember Easily:_**

  | Class | Range (First Number) | No. of Devices | Used By               | Example IP  |
  | ----- | -------------------- | -------------- | --------------------- | ----------- |
  | A     | 1 – 126              | \~16 million   | Large companies       | 10.0.0.1    |
  | B     | 128 – 191            | \~65,000       | Universities, offices | 172.16.5.4  |
  | C     | 192 – 223            | 254            | Homes, small offices  | 192.168.1.1 |
  | D     | 224 – 239            | Multicast only | Streaming, messages   | 224.0.0.5   |
  | E     | 240 – 255            | Not used       | Research only         | 250.1.1.1   |

  # **_Simple Analogy:_**

  | Type of House  | IP Class | Size of Network           |
  | -------------- | -------- | ------------------------- |
  | Huge mansion   | Class A  | Millions of devices       |
  | Big bungalow   | Class B  | Thousands of devices      |
  | Small home     | Class C  | A few hundred devices     |
  | Cinema theatre | Class D  | One sends to many viewers |
  | Lab/test house | Class E  | Reserved for research     |

# What is IPv4 and IPv6?
They are two versions of the Internet Protocol – rules that give every device a unique IP address to identify it on the network.

| Name     | Stands for                  |
| -------- | --------------------------- |
| **IPv4** | Internet Protocol version 4 |
| **IPv6** | Internet Protocol version 6 |

  ### **_Why do we need two versions?_**
  * At first, we used IPv4, which gives about 4.3 billion addresses.
  * But now, we have more people + more devices (phones, TVs, fridges, smartwatches...)
  * IPv4 is running out!
  * So we created IPv6 to solve this.

  ### **_Difference Between IPv4 and IPv6_**

  | Feature                   | IPv4                          | IPv6                                      |
  | ------------------------- | ----------------------------- | ----------------------------------------- |
  | 📏 **Address Size**       | 32 bits (4 numbers)           | 128 bits (8 groups of 4 hex digits)       |
  | 🔢 **Example Address**    | `192.168.1.1`                 | `2001:0db8:85a3:0000:0000:8a2e:0370:7334` |
  | 💡 **Total addresses**    | \~4.3 billion                 | \~340 **undecillion** (almost unlimited)  |
  | ✍️ **Written in**         | Decimal (with dots)           | Hexadecimal (with colons)                 |
  | 🚀 **Speed**              | Slower in large networks      | Faster in large-scale routing             |
  | 🔐 **Security**           | Not built-in                  | Security (IPSec) is built-in              |
  | 🌐 **NAT (used?)**        | Yes, often needed             | Not needed                                |
  | 📦 **Packet size config** | Manual                        | Auto-configured                           |
  | 💬 **Communication**      | Broadcast, unicast, multicast | Unicast, multicast, **anycast**           |
  | 📅 **Introduced**         | 1981                          | 1998                                      |
  | 🧠 **Human-readable?**    | Easy                          | Harder (long address)                     |

# Notation
Notation means how numbers are written in different number systems.

  ### **_1. Decimal Notation (What humans use)_**
  Also called Base 10
  Uses 10 digits: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
  Every place is a power of 10

    Example:
    The number 345 in decimal means:
    = (3 × 100) + (4 × 10) + (5 × 1)
    = (3 × 10²) + (4 × 10¹) + (5 × 10⁰)
    
  ### **_2. Binary Notation (What computers use)_**
  Also called Base 2
  Uses only 2 digits: 0 and 1
  Every place is a power of 2

    Example:
    The number 1010 in binary means:
    = (1 × 8) + (0 × 4) + (1 × 2) + (0 × 1)
    = (1 × 2³) + (0 × 2²) + (1 × 2¹) + (0 × 2⁰)

