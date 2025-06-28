# DAY 2 :
* # Kernel and Shell
  ![image](https://github.com/user-attachments/assets/884fa9e1-3ff3-4c51-b67e-bb392281eb98)
    ### Kernel:
    It is a program that is core of computer's operating system with complete control over everything in the system. It interacts with hardware.
    ### Shell:
    It is a program that acts an interface between user and operating system.
    
    ### Types of Shell:
    ### **_Bash_** :
    Most commmon (friendlist)
      
    A Command-Line Interpreter (Shell)
    Bash stands for Bourne Again SHell.
    It is the program you use to type commands in Linux or Mac. It lets you talk to the computer using text.

    💬 Think of it like:
    A messenger between you and the computer’s brain (kernel).
  
    You type a command like:
  
    **_cd Documents_**
  
    Bash takes it, understands it, and tells the computer what to do.


    ### **_Sh_** :
    Original shell (basic)
  
    ### **_Zsh_** :
    Fancy waiter, more features (managing file system)
  
    ### **_Fish_** :
    Modern interaction (files/programs)
     
    ## Categories:
    ---
    ### **_Commandline shell_**
  
    ![image](https://github.com/user-attachments/assets/e841590f-de47-4e8a-9911-42e79f8f4fc6)

    ### **_Graphical shell_**
  
    ![image](https://github.com/user-attachments/assets/b14725f2-de83-4304-b1a7-1741d80757ff)

* # Linux commands
    ### **_ls_** :
    Shows all files and folders in the current place in the form of a list.
      
    ![image](https://github.com/user-attachments/assets/7c73e51f-c456-42fc-9cc5-43673098771e)
  
    ### **_cd_** :
    Changes the directory (move into a folder).
      
    ![image](https://github.com/user-attachments/assets/e4b50267-293a-4786-b246-5bf2b3764d98)
  
    ### **_pwd_** :
    Prints working directory. Shows where you are right now.
      
    ![image](https://github.com/user-attachments/assets/71149211-c6ed-4062-8f04-4833a4d81fa7)
  
    ### **_whoami_** :
    Who is using the computer. Tells the username.
      
    ![image](https://github.com/user-attachments/assets/2d0babf3-c854-4885-9ba8-e106efe9840d)
  
    ### **_whatis_** :
    Gives short information about a command.

    ### ERROR : Shows nothing appropriate
  
      2 main reasons:
      Man (manual) database is not updated
      The command is unknown or not installed

    ![image](https://github.com/user-attachments/assets/a0b13616-7df3-4251-83e6-bbf6e7d99fbf)


    ### FIXING THE ERROR : Just update the whatis database using:
  
      sudo mandb
      This command builds the database so whatis can find info next time.

    ![image](https://github.com/user-attachments/assets/ee91d0bb-4793-41b0-a763-ecac65194c87)

    ### ERROR RESOLVED :

    ![image](https://github.com/user-attachments/assets/5a9a1502-0c8e-4a48-95a1-f6d1fc3af1d6)

    ### **_whereis_** :
    Tells where the command is. Finds where a program is installed.
      
    ![image](https://github.com/user-attachments/assets/fa4b9c98-c48c-41c0-afe4-3b118c8fd5fe)

    ### **_mkdir_** :
    Create a new directory (folder).
      
    ![image](https://github.com/user-attachments/assets/118a6b10-efda-470b-9b82-dad491e20043)
  
    ### **_rmdir_** :
    Deletes a directory, but only if it's empty.
      
    ![image](https://github.com/user-attachments/assets/1bb99e61-8f87-4385-a51c-c1a9f92bd041)
  
    ### **_cat_** :
    It stands for concatenate. This is used to make file with content. various uses such as- file concatenation, to see the content of the file, copies the file content etc.
      
    ![image](https://github.com/user-attachments/assets/83287531-cee5-4ff5-a15d-e88b7f9a5001)

    ![image](https://github.com/user-attachments/assets/1d942193-7345-4ca6-9512-dcf515ead219)
  
    ### **_touch_** :
    Creates an empty file. No content is written.
      
    ![image](https://github.com/user-attachments/assets/20c932de-dd43-4179-81c4-0e63ae2e3e52)
  
    ### **_nano_** :
    * A text editor in linux
    * Beginner-friendly
    * Simple and clear
      
    **_Commands shown at the bottom_**
      
        Ctrl + O → Save the file (O for Output)
        Ctrl + X → Exit
        Ctrl + K → Cut a line
        Ctrl + U → Paste
      
    ### **_vi_** :
    * It is also a text editor
    * The older, more powerful one
    * Comes pre-installed in all Linux systems
    * Harder for beginners

    ### __vi Modes__
    **_Command mode_** → You move around or delete/copy
  
    **_Insert mode_** → You can type and edit text

      Press i → to go into Insert mode (you can now type)
      Type your content
      Press Esc → to leave insert mode and go to command mode
      Type :w → to save (write)
      Type :q → to quit
      Type :wq → to save and quit
      Type :q! → to force quit without saving
  
    ### **_vim_** : Improved version of vi

      vim = "Vi IMproved"
      Better features, colors, undo/redo, etc.
      Still works with same modes (insert and command)

* # ASSIGNMENT
  ---
  
    ### **_cp_** :
    Makes a copy of a file or directory(folder). The original file or directory is not removed. We can copy one file into another file and also file into a folder known as directory.
      
    ![image](https://github.com/user-attachments/assets/c8fdfa54-d2d4-4a06-9b2e-f5b7c77d1f01)
  
    ### **_mv_** :
    Moves a file from one place to another. It removes the original file after moving to another file or directory.
      
    ![image](https://github.com/user-attachments/assets/09ecc750-93e1-4042-90a5-badd14fcfa80)

    ![image](https://github.com/user-attachments/assets/69ae177c-f140-4a4b-ba8c-45fc044425b3)
    ---
    ---

  # File structure
  A file structure refers to how files and directories (folders) are organized in a system. It’s like a tree where folders (called directories) can contain files or other folders.

  ### **_Files_**
    A file is a container that holds data, such as text, images, videos, code, etc.
    Example: notes.txt, report.pdf, photo.jpg

  ### **_Directories (Folders)_**
    A directory is a special type of file that contains other files or directories.
    Example: Documents, Downloads, Music

  ### **_Tree-Like Structure (Hierarchical)_**
  
      /
      ├── home/
      │   └── kirandeep/
      │       ├── Documents/
      │       │   └── resume.pdf
      │       ├── Music/
      │       └── Pictures/
      │           └── photo.jpg
      ├── bin/
      ├── etc/
      └── var/

      / → Root directory (the top of the structure)
      home/ → A folder inside root
      kirandeep/ → Your personal user directory
      Documents/, Music/, Pictures/ → Subdirectories under your user
      Files like resume.pdf and photo.jpg are stored inside directories

  ![image](https://nepalisupport.wordpress.com/wp-content/uploads/2016/06/linux-filesystem.png)

  #  Path Types
  
  ### **_Absolute Path_**
    Full path from the root
    * Example: /home/amandeep/Documents/resume.pdf
  
  ### **_Relative Path_**
    Path from your current location
    * Example (if you're in amandeep): Documents/resume.pdf
  
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
  
    | Feature           | VirtualBox                          | VMware                              |
    | -------------     | :-----------------                 :| -----------:                        |
    | Cost              | Free and open-source                | Paid                                |
    | Developer         | Oracle                              | VMware Inc.                         |
    | Beginner-Friendly | Yes – easier for beginners          | Yes – but a bit more professional UI|
  | Host OS Support   | Windows, Linux, macOS               | Windows, Linux(macOS not officially)|
  | Guest OS Support  | Windows, Linux, macOS, BSD          | Windows, Linux, (macOS unofficial)  |
  | Performance       | Slightly slower                     | Slightly faster                     |
  | Advanced Features | Snapshots, shared folders, USB      | More advanced features              |
  | Best Use Case     | Learning, personal VMs, open source | More professional use               |
  


  

    

  

 
    
     
