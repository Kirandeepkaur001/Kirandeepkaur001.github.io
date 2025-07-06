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
  * **_Send data_** – like sending an email or uploading a photo.
  * **_Receive data_** – like watching a video or opening a website.
  * **_Store and share_** – like sharing a file or hosting a website.

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

![image](https://github.com/user-attachments/assets/15202932-d867-4397-93e0-d1cc38885150)

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

# Network ID and Host ID
In computer networks (especially in IP addresses), an IP address is divided into two parts:

  ### **_1. Network ID_**
  * It identifies the network to which a device (computer, printer, etc.) belongs.
  * All devices on the same network will have the same Network ID.
  * Example: In a company, all computers in one office floor may have the same network ID.

  ### **_2. Host ID_**
  * It identifies a specific device (host) within the network.
  * It must be unique for every device in that network.
  * So, two computers cannot have the same Host ID in one network.

  ### **_ Example (IPv4):_**
      Let’s say the IP address is:
      192.168.1.10
      And the subnet mask is:
      255.255.255.0
      
      Network ID = 192.168.1.0
      Host ID = 0.0.0.10
      This means the device is number 10 in the 192.168.1.0 network.

# Classful Addressing
Classful Addressing is an old method of dividing the IPv4 address space into fixed-size blocks called classes.

![image](https://github.com/user-attachments/assets/9691741f-6428-490d-975e-6e3d5bad725c)

![image](https://github.com/user-attachments/assets/97215857-7be2-4465-9f17-e792b92b510c)

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
* **_Prefix = Network part_**
* **_Suffix = Host part_**

Example:
IP: 10.0.0.1
Prefix: 10
Suffix: 0.0.1
---

  ### **_Class A – For Very Big Networks_**
  Used by: Very large companies or government

  Example:
  Imagine you’re running a big company like Google or Amazon with millions of devices.
  You need a lot of IP addresses in one network.

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
  Imagine your university or office has thousands of computers.
  
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
  You have a small office with fewer than 250 computers.

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

  ###  **_Full Table to Remember Easily:_**

  | Class | Range (First Number) | No. of Devices | Used By               | Example IP  |
  | ----- | -------------------- | -------------- | --------------------- | ----------- |
  | A     | 1 – 126              | \~16 million   | Large companies       | 10.0.0.1    |
  | B     | 128 – 191            | \~65,000       | Universities, offices | 172.16.5.4  |
  | C     | 192 – 223            | 254            | Homes, small offices  | 192.168.1.1 |
  | D     | 224 – 239            | Multicast only | Streaming, messages   | 224.0.0.5   |
  | E     | 240 – 255            | Not used       | Research only         | 250.1.1.1   |

  ### **_Simple Analogy:_**

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

#  MAC Address
A MAC address (Media Access Control address) is a unique ID given to every device's network card(hardware part in your computer, laptop, phone, or any device that allows it to connect to a network like the internet or LAN (Local Area Network)

(It helps devices identify each other on a local network (like your home Wi-Fi).

#  Domain Name Server (DNS)
* A Domain Name Server (DNS) is like the phonebook of the internet.
* It helps your computer find the real address (IP) of a website you want to visit.

  ### **_Why do we need DNS?_**
      www.google.com

      But computers don’t understand names — they understand **IP addresses**, like:
      ``142.250.195.78``
      
      So, DNS helps to:
      🔄 **Translate** `www.google.com` → `142.250.195.78`
      
      ---
      
      ### 📞 Simple Analogy:
      
      You know your friend’s name is **Amandeep**,  
      But your phone needs their **phone number** to call.
      
      So, you check your phonebook:
      - Name: Amandeep  
      - Number: 9876543210  
      
      ✅ That’s what DNS does — it looks up the **IP address** for a **website name**.
      
      ---
      
      ### 🔄 Step-by-Step: How DNS Works
      
      1. 🧑 You type: `www.youtube.com` in your browser  
      2. 🌐 Your computer asks the DNS: "What is the IP of youtube.com?"  
      3. 🧠 DNS replies: "It is `142.250.195.78`"  
      4. 🚀 Your browser goes to that IP and opens the website!
      
      ---
      
      ### 🧠 Without DNS:
      You would have to **remember numbers** like `142.250.195.78` instead of easy names like `youtube.com`.
      
      ---
      
      ### 📌 Key Terms:
      
      | Term        | Meaning |
      |-------------|---------|
      | **DNS**     | Domain Name Server — translates website names to IP addresses |
      | **IP Address** | A number that identifies each device or website on the internet |
      | **Domain Name** | The name you type (like google.com) |
      
      ---
      
      Let me know if you want to see how to **check DNS settings** or how DNS errors are fixed!

# Default Gateway
A default gateway is the device (usually a router) that your computer uses to connect to other networks, like the internet.
* Think of it as the "exit door" from your local network to the outside world.

  ### **_Simple Analogy:_**
  * Imagine your house (home network) and a main gate (default gateway).
  * Inside the house, all rooms can talk to each other (your devices: phone, laptop, TV).
  * But to go outside (like to a shop or school = internet), you must use the main gate.
  * That main gate is the default gateway.

  ### **_Example:_**
  * Your laptop’s IP address = 192.168.1.5
  * Your router’s IP address = 192.168.1.1
  * Here, 192.168.1.1 is the default gateway.
  So when your laptop wants to open **www.google.com**, it sends the request to 192.168.1.1 (router) — the default gateway — which then connects to the internet and brings back the website.

# Difference Between Unicast, Broadcast, and Multicast

| Feature    | **Unicast**           | **Broadcast**           | **Multicast**                    |
| ---------- | --------------------- | ----------------------- | -------------------------------- |
| Sends to   | One device            | All devices on network  | Selected group of devices        |
| IP Example | `192.168.1.10`        | `255.255.255.255`       | `224.0.0.1` (etc.)               |
| Used for   | Private communication | Network discovery, DHCP | Streaming, IPTV, conferencing    |
| Efficient? | ✅ (for one)           | ❌ (wastes bandwidth)    | ✅ (saves bandwidth vs broadcast) |

# Types of Cables

### **_1. Twisted Pair Cable_**
Looks like: Two or more wires twisted together

![image](https://github.com/user-attachments/assets/411cafca-41cc-4e7b-9991-87904e444571)

  ### **_Types:_**
  * UTP (Unshielded Twisted Pair) – used in LAN
  * STP (Shielded Twisted Pair) – used where protection from noise is needed

  ### **_Common Use:_**
  Ethernet cables (like Cat5e, Cat6 used in offices, homes)

  ### **_Speed & Distance:_**
  * Up to 1 Gbps or more
  * Around 100 meters (for good quality)

  ### **_Features:_**
  * Cheap and flexible
  * Easy to install
  * Affected by electrical noise (less protected)

### **_2. Coaxial Cable_**
Looks like: A single copper wire in the center, surrounded by insulation, metal shield, and outer cover (like a TV cable)

![image](https://github.com/user-attachments/assets/5645a684-253c-4a3c-90fc-d9db79d47dc5)

  ### **_Common Use:_**
  * Cable TV
  * Internet through cable modems
  * CCTV cameras

  ### **_Speed & Distance:_**
  * Up to 10 Mbps to 1 Gbps
  * More distance than twisted pair

  ### **_Features:_**
  * Better protection from interference
  * Thicker and harder to bend than twisted pair

### **_3. Optical Fibre Cable_**
Looks like: Thin glass or plastic strands inside a protective cover — uses light, not electricity

![image](https://github.com/user-attachments/assets/c048ccc8-d6c8-4dfe-919f-20580ace3e5b)

![image](https://github.com/user-attachments/assets/a1c0205e-0d9c-477b-b083-d08a2b389abb)

  ### **_Common Use:_**
  * High-speed internet (FTTH - Fiber To The Home)
  * Long-distance communication
  * ISPs, backbone of internet

  ### **_Speed & Distance:_**
  * Very high speed (up to Tbps)
  * Can go kilometers without signal loss

  ### **_Features:_**
  * No electrical interference
  * More expensive but super fast
  * Fragile (glass inside)

# Subnetting
It helps you to utilize your network bandwidth(rate at which data is actually transmitted over network. It should be maximum. Units-bits per sec or bts.) more intelligently. The practice of dividing a network into two or more networks is **Subnetting**.

![image](https://github.com/user-attachments/assets/35dcc036-6b87-4bfa-ae2f-e5d1fc5463b7)

  ### **_Notations: CIDR vs. Decimal_**
  Subnet masks are expressed either in CIDR notation or dotted-decimal format. CIDR notation simply appends a slash followed by the number of ones in the mask. For example, /24 equates to 255.255.255.0. Meanwhile, dotted-decimal format writes the mask as four octets separated by dots.
  
![image](https://github.com/user-attachments/assets/77f873c8-5c8c-41f6-88ee-738b99b5eb6f)

![image](https://github.com/user-attachments/assets/a2ad4e6a-affc-46d4-b8a5-9dd1cf97a59b)

# Latency
Delay in data on passing from one point to another. It should be less (< millisecond).

# Network ID
If we divide network into five different sub-network, every sub-network will have unique network IP.
* It represents the whole network, not a specific device.
* It is the first address in any IP range.
* Used by routers and computers to identify the network itself.

    Example:
    If you have a network 192.168.1.0/24
    The Network IP is: 192.168.1.0
    (It means: "This is the 192.168.1.x network")

# Broadcast ID
The last IP address of your subnet  range.
* It is used to send data to all devices in the network.
* It is the last IP address in the range.
* When a message is sent to the broadcast IP, all devices on the network receive it.

    Example:
    For the network 192.168.1.0/24
    The Broadcast IP is: 192.168.1.255
    
    So, if a device sends data to 192.168.1.255, all devices from 192.168.1.1 to 192.168.1.254 will receive it.

# Subnet mask
A subnet mask is like a divider that splits an IP address into:
* Network part (which network it belongs to)
* Host part (which device in that network)
It helps computers know: “Are you in my network or are you in another network?”

