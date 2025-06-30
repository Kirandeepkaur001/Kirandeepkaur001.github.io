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

# Wild Cards (Globbing)
* Wildcards are special symbols that help you find or work with multiple files without typing every name.
* Think of them like shortcuts when you're dealing with lots of files.

### **_Most Common Wildcards_**

| Wildcard | Meaning                  | Example         | What It Matches              |
| -------- | ------------------------ | --------------- | ---------------------------- |
| *    | Anything                 | *.txt         | All files ending with .txt like notes.txt, file.txt|
| ?    | One character            | file?.txt     | file1.txt, fileA.txt, but not file10.txt          |
| [ ]  | One character from a set | file[1-3].txt | file1.txt, file2.txt, file3.txt                   |

### 1. **_*.txt_**

### 2. **_?.txt_**

### 3. **_[].txt_**
