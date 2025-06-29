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

# sh shell
    sh is a basic shell (a command-line interpreter).
    It reads and runs commands, like echo, ls, cd, etc.
    You use it to run scripts written in a file.
    Think of sh like a robot that reads your .sh file line by line and does what you tell it to.

# .sh file
    A .sh file is just a text file full of Linux commands.
    It usually starts with this line:
    #!/bin/sh
  
    That line tells the computer:
    “Use the sh shell to run this file.”

**_What happens in the background_**

  Imagine sh is a person reading your .sh file:
  sh says: Okay, I see "echo Hello", I will say Hello.


  
      

  

    

  

 
    
     

