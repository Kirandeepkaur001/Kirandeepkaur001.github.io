# DAY 3 :
  # Dual Boot
  Two Operating Systems on One Computer. You can choose which system to use when your computer starts.
  
  # Bare Metal Installation
  Installing an OS directly on a physical computer, not inside VMware. The OS can be installed using hard disk or pen drive.
  
  # Meta Installation
  Installing a package that installs many other related packages. It's like a "starter kit" — you install one thing, and it brings a bunch of things with it.

      sudo apt install ubuntu-desktop
      ubuntu-desktop is a meta package

      It installs:
      * File manager
      * Desktop environment
      * Login screen
      * Wallpaper
  
  # Partitioning Scheme
  Dividing your hard disk into sections, so that each part can be used for a different purpose. Linux uses multiple partitions to keep the system organized, secure, and flexible.
      One partition for Windows
      Another for Linux
      Another for Data

  ### **_MBT(Master Boot Record)_**
  The installer automatically creates partitions. We don’t have to manually set the root, swap, home, etc. It is suitable for old systems.
  
  ### **_GPT(Guided Partitioning Scheme)_**
  We have to manually set the partitions. It is suitable for new systems.

  # ISO File : A digital version of a CD/DVD
  It’s a single file that contains all the files needed to install an operating system. For example - A zip file that holds a full OS installer (like Ubuntu or Windows).
  
  # VMware :  Virtual Computer Inside Real Computer
  It's software that lets you run another operating system inside a window, like an app.
      You have Windows.
      You install VMware.
      You run Ubuntu Linux inside it — in a separate window.
      You can use both at the same time..
      
  # Comparison between VirtualBox and VMware
  Both are software that create virtual computers (VMs) inside real computer. We can run Linux inside Windows, or Windows inside Linux, and more..

  The difference between virtual box and VMware-
  
  | Feature | VirtualBox | VMware |                              
  | ------------------| ------------------ | ----------- |    
  | Cost              | Free and open-source | Paid |                                
  | Developer         | Oracle | VMware Inc. |                        
  | Beginner-Friendly | Yes – easier for beginners | Yes – but a bit more professional UI |
  | Host OS Support   | Windows, Linux, macOS | Windows, Linux(macOS not officially) |
  | Guest OS Support  | Windows, Linux, macOS, BSD | Windows, Linux, (macOS unofficial) |  
  | Performance       | Slightly slower | Slightly faster |                     
  | Advanced Features | Snapshots, shared folders, USB | More advanced features |              
  | Best Use Case     | Learning, personal VMs, open source | More professional use |

  # echo
  echo is a command used in Linux to display (print) text or messages on the terminal. Think of it like speaking something on the screen.

  **_syntax :_** echo [options] [string]
  
  **_examples :_** 

  ![image](https://github.com/user-attachments/assets/b4a22efb-6a4d-4554-9751-3f0ce0987abc)

  ![image](https://github.com/user-attachments/assets/f0ed4a51-df6d-4dcf-b920-5154f6254b3e)
  
  ![image](https://github.com/user-attachments/assets/72898c0e-3e10-4aa5-850b-e07fbb2d6cb0)


| Command                  | What it does                   |
| ------------------------ | ------------------------------ |
| `echo Hello`             | Prints Hello                   |
| `echo -n "Hi"`           | No new line at end             |
| `echo -e "a\nb"`         | New line between a and b       |
| `echo -e "x\ty"`         | Adds a tab between x and y     |
| `echo $HOME`             | Shows value of variable `HOME` |
| `echo "This is \$5"`     | Prints `$5` with `$` visible   |
| `echo "text" > file.txt` | Saves text to file.txt         |
| `echo "add" >> file.txt` | Adds text to end of file.txt   |

# Shell Programming
    Shell programming (or shell scripting) means:
    Writing a set of Linux commands in a file, and
    Letting the shell (like bash or sh) run them one by one.
    File ends with .sh (e.g., script.sh)

* # ASSIGNMENT
  ---

  ### **_Programs using Shell programming_**

  ### **_SIMPLE ADDITION_**
  
  ![image](https://github.com/user-attachments/assets/9e37ddee-202e-4f73-aa5a-28d8042cf6eb)

  ![image](https://github.com/user-attachments/assets/eed7090f-17f6-4e8a-812a-dd8b1aefe07c)

  ### **_COMPARING TWO NUMBERS_**

  ![image](https://github.com/user-attachments/assets/9665dbe9-d2dd-4c9b-acf2-8968b46f196b)

  ![image](https://github.com/user-attachments/assets/87c93ed5-7a6a-4d84-9d54-15139a4a2f3d)

  ### **_PRINT NO. FROM 1 TO 5_**

  ![image](https://github.com/user-attachments/assets/02555458-09b8-428b-b58f-f2d2070ff3ad)

  ![image](https://github.com/user-attachments/assets/1255dfcb-3126-404c-8f80-4730b5ea4e98)
  
  ### **_MULTIPLICATION TABLE_**

  ![image](https://github.com/user-attachments/assets/815e5721-cb05-4a76-a8ed-369441cb13a0)

  ![image](https://github.com/user-attachments/assets/8ba18cb5-c762-4b39-b569-efef3b8cb7b7)
  
  ### **_BIO DATA_**

  ![image](https://github.com/user-attachments/assets/9ac40c52-f3d5-4b93-9c17-279fc08a5052)

  ![image](https://github.com/user-attachments/assets/da1de9b0-47ee-49fe-adbb-8984aaa81a83)

  # File and Directory Permission

  ### **_Change mode(chmod)_**
    Change file/directory permissions
    It controls who can read, write, or run a file.
    Giving keys to people to open, write, or use a file.

  ### **_Why do we need it?_**
    To control who can do what with a file:
    Read (r)
    Write (w)
    Execute (x)

  ### **_Types of Users in File Permissions_**
  
  | Symbol | User Type | Who?                        |
  | ------ | --------- | --------------------------- |
  | u    | user      | The owner of the file         |
  | g    | group     | Other users in the same group |
  | o    | others    | Everyone else                 |
  | a    | all       | user + group + others         |

  ### **_Types of Permissions_**
  
  | Symbol | Permission | Meaning                                   |
  | ------ | ---------- | ------------------------------------------|
  | r    | Read       | Can view/open the file                      |
  | w    | Write      | Can modify/edit the file                    |
  | x    | Execute    | Can run the file (if it’s a script/program) |

  ### **_Two Ways to Use chmod_**

    ### **_1. Symbolic Mode (Easy to read)_**
    | Command           | What it Does                  |
    | ----------------- | ----------------------------- |
    | chmod u+x file.sh | User can run the file         |
    | chmod g-w file.sh | Group can't edit the file     |
    | chmod o+r file.sh | Others can read the file      |
    | chmod a+x file.sh | Everyone can execute the file |
  
    ### **_2. Numeric Mode (Uses numbers)_**
        Each permission is a number:
        r = 4
        w = 2
        x = 1

        You add them:
        7 = read (4) + write (2) + execute (1)
        6 = read + write
        5 = read + execute
        4 = read only

        Example:
        chmod 755 file.sh

        7 → user = read, write, execute
        5 → group = read, execute
        5 → others = read, execute

# Cases

### 1. Make a Script Executable
  You wrote a shell script and want to run it directly.

### 2. Make a File Read-Only
  You want to protect a file so no one (even you) can accidentally edit it.
      
        How to read the file:
        These commands will work:
        cat important.txt
        less important.txt
        more important.txt
        head important.txt
        tail important.txt
        ✔️ You can view the content, but ❌ cannot edit or save changes.

### 3. Give Execute Permission to All Users
  You have a program/script. Everyone can execute it(user, group, others).
        
### 4.  Remove All Permissions (Lock a File Completely)
  Temporarily block all access to a file.
        
### 5. Set Full Access for User, Read-Only for Others
  You want to edit a file, but others can only view it.

# ASSIGNMENT 
---
  ### Change owner(chown)
    Change the owner of a file
    Sometimes, files are created by the system or another user.
    You can use chown to give ownership to yourself or someone else.

      It lets you change the owner and/or group of a file or directory
      Every file in Linux has:
      An owner (a user)
      A group (a set of users)

      Example:
      File: report.txt
      Owner: amandeep
      Group: students

  ### **_Syntax_**
  chown [OPTIONS] user[:group] file
 
  | Part   | Meaning                      |
  | ------ | ---------------------------- |
  |OPTIONS |extra settings to control how chown works|
  | user   | new owner (required)         |
  | :group | optional – new group         |
  | file   | the file or folder to change |

  ### **_Examples_**
  
  | Command                         | Meaning                                        |
  | ------------------------------- | ---------------------------------------------- |
  | chown amandeep file.txt       | Make `kirandeep` the owner of `file.txt`        |
  | chown :staff file.txt        | Change only the **group** to `staff`           |
  | chown kirandeep:staff file.txt | Change both **owner** and **group**            |
  | sudo chown kirandeep file.txt  | Run with **root powers** (if you're not owner) |

### 1. Change Owner Only
This changes only the user who owns the file. The group stays the same.



### 2. Change Only the Group
This changes only the group.



### 3. Change Owner and Group
This changes both the owner and the group.



### 4. Change Ownership of a Folder and Its Contents (Recursive)
-R changes ownership of all files and directories(folders) inside myfolder



### 5. Check Ownership of a File
Using ls -l file.txt



### 6. Use sudo If You're Not the Owner
sudo chown user file.txt


---

# Redirection
Redirection in Linux is used to **send output to files**, **take input from filesinstead of keyboard(redirection)**, or **append data** instead of showing it on the screen.

| Type | Meaning                        | Syntax & Example                    |
|------|--------------------------------|-------------------------------------|
| `>`  | Write/overwrite to a file      | `echo hi > file.txt`                |
| `>>` | Append to a file               | `echo hi >> file.txt`               |
| `<`  | Input redirection (read from a file) | `sort < file.txt`             |
      
# Pipes
Take the file of particular one extension like a filter. A pipe is used to connect the output of one command to the input of another.

Command 1 → output → becomes input for → Command 2

### **_Syntax_**
command1 | command2

### **_Example_**
  ls | sort
  
  ls -> lists files
  sort -> sorts them alphabetically
  Output -> A sorted list of your files

### **_Why to use pipes?_**
  Pipes let you:
  1. Combine multiple small commands
  2. Avoid temporary files
  3. Process data quickly
    

  

 
    
     

