# Open Source SW

### Kernel and Shell

Kernel:Core of OS that controls and communicates with hardware resource
Shell:Inter face that allows users to communicate with kernel:bash,zsh,…  Users runs applications and give commands through shell

### Linux

-Open-source Unix-like operating systems and kernels, first released by Linus Torvalds in 1991  
-Popular distributions include Debian,Fedora,and Ubuntu,among many others  
-Leading OS on servers (over 96.4% of the top 1 million web servers)  
-Also runs on embedded systems and mobile systems (Android)  
-Most widely-used platform for open source software development  
-Secure and stable  
-Runs on CLI(Command Line Interface),but many distributions support GUIs as well

---
## CLI (Command Line Interface)vs.GUI (Graphical User Interface)
#### CLI

-Have to remember commands  
-Keyboards, mostly  
-Relatively fast  
-Scripts enable automation and records  
-Basic environment for developers

#### GUI

-EasytouseandIntuitive  
-Mouse mostly Some + keyboard shorcuts  
-Relatively slow  
-Manual labors required for repetitive tasks  
-For daily users

---

# Shell Commands

pwd: shows the current path in a hierarchical directory
cd: change directory  
ls: list files and directories

  ***ls*** can attach some arguments 
   
  -l : show detailed information (longformat)  
  -lh same as above, but size in units

 ### arguments
  
  / : root  
  . : currentdirectory  
  .. : upper-leveldirectory  
  ~ = homeofcurrentuser  
  /[directoryname] : absolute path  
  ./[directoryname] : relativep ath  
  ../[directoryname] : relative path

### Manipulation
 ***Warning*** These commands may delete or overwrite your files and directories! 
 cp : copy files and directories
  
  cp ***file 1*** ***file 2*** : Copies the cotents of ***file 1*** into ***file 2***. If ***file 2*** does not exist, it is created. 
  
  '' -i ***file 1*** ***file 2*** : Like above, but Prompted before overwrite. 
  
  '' ***file 1*** ***dir 1*** : Copy the contents of ***file 1*** inside of direcroty ***dir 1***.
  '' -R ***dir 1*** ***dir 2*** : Copies the cotents of ***dir 1*** into ***dir 2***. If ***dir 2*** does not exist, it is created. Otherwise, it creates a directory named ***dir 1*** kwithin directory ***dir 2***.
  
  mv : move files and directories or rename them
  
  rm: delete files and directories

  mkdir: make a new directory

  $ exit : exiting terminal
   

 ### TIPS

 Autocompletion : Press "tab" key 

 Past commands : Press“uparrow”key
 
 clear : clear the terminal window (not delete)

---
## Standard Output
 - **>** & ***cat*** : '>' is a redirect output command to create and save the output in a file, 'cat' displays the content of a text file.
 - **>>** : Appends output to an extisting file or create and write to a new file if it doesn't exist.
 - **<** : By default, standard input is keyboard. but redirect input from a file using '<', You can mix '<' & '>'.
 - **|** (pipelines) : feeds output of previous command to input of next command. EX. command 1 | command 2 = output command 2 using command 1.
 - **echo** : reply all sentence behind itself. but 'echo *' means output all files in directory where we current working. 'echo ~' mean showing user's home directory.
 - **\** (backslash) : ignore line change you can keep write the command ignore lines after using '\' (when command seems to be longer than usual).

---
## Permissions
 Linux is a multi-user system. File and directories have a permission asigned differently
  -<u>rwx</u>rwxrwx : r- read, w- write, x- execute. fore 'rwx' is higher executor, it divided owner / group/ others. EX. -rw-rw-r--
  




 
