# DAY 4 :

# File Compression
It means to compress a file and making file smaller so it takes up less space on your computer.

### **_Why Do We Compress Files?_**
* To save space on your computer
* To send files faster (like in email or WhatsApp)
* To group many files into one (e.g., a ZIP file)

### **_Common Types of Compression_**
* ZIP – Most common (like file.zip)
* RAR – Another type (like file.rar)
* TAR.GZ – Common on Linux systems

### GZIP(GNU zip)
Used to compress files to make file smaller in size.

### **_Syntax in Linux_**
gzip filename

If we want to **UNZIP** the file, use **gunzip**

### **_If not to delete the original file use -k_**
gzip -k filename

![image](https://github.com/user-attachments/assets/a2f07225-46c1-4c5a-a1c7-86113e3a09a6)

# Wild Cards (Globbing)
* Wildcards are special symbols that help you find or work with multiple files without typing every name.
* Think of them like shortcuts when we are dealing with lots of files.

### **_Most Common Wildcards_**

| Wildcard | Meaning                  | Example         | What It Matches              |
| -------- | ------------------------ | --------------- | ---------------------------- |
| *    | Anything                 | *.txt         | All files ending with .txt like notes.txt, file.txt|
| ?    | One character            | file?.txt     | file1.txt, fileA.txt, but not file10.txt          |
| [ ]  | One character from a set | file[1-3].txt | file1.txt, file2.txt, file3.txt                   |

![image](https://github.com/user-attachments/assets/673c8945-a974-44ec-90a7-d94faa1c71b2)

  ### 1. **_*.txt_**

  ![image](https://github.com/user-attachments/assets/96ffc29b-13db-4cd4-a55e-568271a16b8d)

  ### 2. **_?.txt_**

  ![image](https://github.com/user-attachments/assets/4415f6ab-3979-44e1-80c9-d1471ee5d557)

  ### 3. **_[ ].txt_**

  ![image](https://github.com/user-attachments/assets/9c555bea-1efc-4ee8-be18-65e9f11b59b0)

  ### 4. **_Match files that start with fixed letter_**

  ![image](https://github.com/user-attachments/assets/652785cd-d29c-49d6-be47-0aaac4144bba)

# ASSIGNMENT
---

### Quoting and Escaping Characters

When we type something in the Linux terminal, sometimes our text includes special characters like:
* Space ( )
* Dollar sign ($)
* Asterisk (*)
* Quotes (" or ')
These have special meanings, so if we want the computer to treat them as normal characters, we need to use quoting or escaping.

### **_Escaping_**
Escaping means protecting a character so the terminal doesn't give it a special meaning. Use backslash ( \ ) for escaping.

![image](https://github.com/user-attachments/assets/c9e85f33-d73d-45c9-ad03-594b74bb7fda)

### **_Quoting_**
Quoting is putting your text inside quotes so special characters don’t get a special meaning.

  ### **_1. Single Quotes ' '_**
  * Treat everything inside as plain text.
  * Nothing gets special meaning.

  ![image](https://github.com/user-attachments/assets/d5d7fffb-1bb7-4e42-ab68-6c7b3034a5ce)

  ### **_2. Double Quotes " "_**
  * Treat most things as plain text, but variables and commands still work.

  ![image](https://github.com/user-attachments/assets/43b24721-636f-4e37-9d88-9c5428802b5e)

  ---

  # Hardware Parts

  ### **_1. Basic Computer Architecture_**

  | Term                  | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **PC (Hardware)**     | Physical components of a computer.                     |
  | **System Software**   | OS installed on hardware (e.g., Windows, Ubuntu).      |
  | **Application Software** | Installed on OS (e.g., MS Word, Chrome, VLC).       |
      
  ### **_2. CPU & Internal Components_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **CPU**               | Central Processing Unit; brain of the computer.        |
  | **Motherboard**       | Main circuit board connecting all components.          |
  | **RAM**               | Volatile memory; data lost on shutdown.                |
  | **ROM**               | Non-volatile memory; stores firmware.                  |
  | **Cache**             | Very fast memory between CPU and RAM.                  |
  | **Registers**         | Small, fast memory inside CPU for temporary data.      |
  | **Control Unit (CU)** | Directs data flow and operations in CPU.               |
  | **ALU**               | Performs calculations and logic.                       |
  | **Clock**             | Synchronizes CPU operations using electrical pulses.   |
  | **Transistors**       | Basic switching units used in processing.              |
  | **Chipset**           | Controls communication; Northbridge and Southbridge.   |
  | **CPU Socket**        | Slot where CPU is mounted; fan usually above it.       |
      
  ### **_3. Storage Devices_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **Hard Disk (HDD/SSD)** | Permanent storage for OS, apps, and files.           |
  | **RAM**               | Temporary, fast memory used during system operation.   |
  | **Cache**             | Small, faster memory for urgent data access.           |
  | **Floppy Disk**       | Old magnetic storage medium (now obsolete).            |
  | **CD/DVD**            | Optical media used to read/write data.                 |
  | **BD (Blu-ray Disk)** | High-capacity optical disk for HD media and backups.   |
      
  ### **_4. Power & Booting_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **Power Supply (SMPS)** | Converts AC to DC; supplies power to components.     |
  | **UPS**               | Battery backup for power outages.                      |
  | **CMOS Battery**      | Maintains BIOS settings and system time.               |
  | **Boot Process**      | Power on → ROM → Bootstrap Loader → OS loads in RAM.   |
      
  ### **_5. Input/Output & Display_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **Monitor**           | Output device to display visuals.                      |
  | **HDMI Port**         | High-definition video output for projectors/displays.  |
  | **VGA Port**          | Older analog video output; needs converter for HDMI.   |
  | **Display Adapter**   | Processes and displays graphics (GPU).                 |
  | **TV Tuner Adapter**  | Enables TV signal input to PC.                         |
      
  ### **_6. Networking & Communication_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **LAN (Local Area Network)** | Network connecting nearby computers.            |
  | **Modem**             | Converts digital ↔ analog signals for internet.        |
  | **LAN Card / NIC**    | Allows PC to connect to network via cable.             |
      
  ### **_7. Other Components & Concepts_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **Drivers**           | Software that lets OS interact with hardware.          |
  | **BIOS Chip**         | Firmware chip that starts hardware and loads OS.       |
  | **Peripheral Devices**| External devices like mouse, keyboard, printer, etc.   |
  | **PCI Slots**         | Expansion slots for adding cards (e.g., sound, LAN).   |
  | **Expansion Slots**   | Slots for adding extra hardware (graphics, TV cards).  |
  | **SATA Ports**        | Connect HDDs and SSDs to motherboard.                  |
  | **Beep Sound**        | POST error codes (e.g., via speaker/copper coil).      |
  | **Cooling System**    | Fans or heat sinks to prevent overheating.             |
  | **Configuration**     | System specs: RAM, CPU speed, storage, brand, etc.     |

# Registers

Registers are tiny, super-fast storage locations inside the CPU. They hold data and instructions that the CPU is currently working on. Registers are the fastest type of memory because they are directly part of the processor.

* Very small storage inside the CPU
* Store data the CPU needs immediately
* Faster than cache and RAM
* Used to perform calculations and operations quickly

# Motherboard
The motherboard is the main printed circuit board (PCB) in a computer or electronic device. It serves as the central backbone that connects and allows communication between all hardware components such as the CPU, memory (RAM), storage devices, power supply, and peripherals.

![WhatsApp Image 2025-06-30 at 11 38 07_11aba076](https://github.com/user-attachments/assets/062e352b-2162-4838-9b3b-050119121700)


