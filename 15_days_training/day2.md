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

    ### **_man_** :
    man stands for manual — it shows the official manual for most Linux commands. It's like a help book 📘 built into Linux that explains how a command works.

        Syntax:
        man command_name
        man ls

        Shows detailed documentation for the ls command:
        * Options (like -l, -a)
        * Usage examples
        * Author info
  
        Press:
        Arrow keys to scroll
        q to quit and go back to terminal

    ### **_help_** :
    help shows quick instructions for shell built-in commands (like cd, echo, if, for).

        Syntax:
        help command_name
        help cd
        Shows how cd works (used to change directory)

  ### Difference Between man and help :
  
  | Feature               | `man`                                  | `help`                             |
  | --------------------- | -------------------------------------- | ---------------------------------- |
  | Works for             | Most Linux commands (e.g., `ls`, `cp`) | Shell built-ins (e.g., `cd`, `if`) |
  | Gives detailed info   | ✅ Yes                                  | ❌ Short & basic                 |
  | Used like             | `man ls`                               | `help cd`                          |
  | Need to quit with `q` | ✅ Yes                                  | ❌ No                            |


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

    ![image](https://github.com/user-attachments/assets/8c438089-333a-4111-80d2-ae1ced0730f3)

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
    
  ![image](https://github.com/user-attachments/assets/dce7beeb-d812-4a89-8e71-d2e9bd39e65f)

  ![image](https://github.com/user-attachments/assets/d55b492c-eece-43fd-a27b-478701451766)

* # File System Software
  It’s how your computer organizes and keeps track of files. When you save a file, your computer needs to know:
  * Where it’s stored
  * What it’s called
  * What kind of file it is
  * Who owns it
  * How big it is
  This job is done by the File System — a type of software built into the operating system.

* #  File Structure in Operating Systems (Linux/Windows)
A file structure refers to how files and directories (folders) are organized in a system. It’s like a tree where folders (called directories) can contain files or other folders.

  **_Basic Concepts_**
  
  **_Files_** : A file is a container that holds data, such as text, images, videos, code, etc. Example: notes.txt, report.pdf, photo.jpg

  **_Directories (Folders)_** : A directory is a special type of file that contains other files or directories. Example: Documents, Downloads, Music

  ### **_Tree-Like Structure (Hierarchical)_**

      /
      ├── home/
      │   └── amandeep/
      │       ├── Documents/
      │       │   └── resume.pdf
      │       ├── Music/
      │       └── Pictures/
      │           └── photo.jpg
      ├── bin/
      ├── etc/
      └── var/

  **_Explanation:_**
  * / → Root directory (the top of the structure)
  * home/ → A folder inside root
  * amandeep/ → Your personal user directory
  * Documents/, Music/, Pictures/ → Subdirectories under your user
  * Files like resume.pdf and photo.jpg are stored inside directories


 
    
     
