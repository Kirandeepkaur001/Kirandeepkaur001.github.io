# Day 7 :

### Host
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

### Protocol
A protocol is like a set of rules that computers follow to communicate with each other.

  ### **_ Example:_**
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

### IP Address
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

  ### **_Types of IP Addresses:_**

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

### Classes of IP Address 
When the internet was first created, people needed a way to give unique IP addresses to all devices, whether:
* A huge company with millions of computers
* A small business with just 10 computers
  
To make IP addresses easy to manage, they are divided into 5 classes: Class A, B, C, D, and E

These classes help decide:
* How many devices can be in a network
* Whether the IP is used for normal devices, multicasting, or experiments

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

🅱️ Class B – For Medium Networks
🏫 Used by: Universities, medium-size companies

📦 Example:
Imagine your university or office has thousands of computers.

First number: 128 to 191

Looks like: 172.16.0.1, 150.25.10.5

You get:

Around 16,000 networks

Each network can have 65,000 devices

Subnet Mask: 255.255.0.0

🧠 Think: B = Big, but not the biggest






