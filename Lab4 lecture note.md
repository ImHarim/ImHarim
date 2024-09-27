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
   

 ### TIPS

 Autocompletion : Press "tab" key 
 Past commands : Press“uparrow”key
 clear : clear the terminal window (not delete)
