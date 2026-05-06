Linux is a free, open-source os. 
Linux is defined by its Kernel which is core components of os.
Kernel allows software to communicate with a computer hardware. 
All Linux systems run a Linux kernel. 
Linux Distribution: Arch, Debain, Red Hat, Slackware and more.

For projects we gonna user virtual machines which no effect on our real computer: 
  VirtualBox which runs on Windows, macOS and Linux. 
  Within my virtual machine (VirtualBox) Im gonna use Ubuntu Desktop Linux Distribution which provides user-friendly Linux env.
After installation (Virtual box and ubuntu), we gonna create the virtual machine inside the VirtualBox:
  Click on "New" >> give a name to the machine >> type set to Linux >> version set to Ubuntu (64-bit) >> next >> set memory as at least 4096MB >> next >> create a virtual hard disk now >> next and VDI >> next and Dynamically allocated >> set 100000GB not 10 >> create.
  The Virtual MAchine Ubuntu was created. Click on it and choose settings on the right window. >> Storage section >> Find the "Empty" slot >> click on the CD icon >> choose a disk file >> navigate the downloads directory in my computer and choose open ubuntu desktop installer i previously downloaded >> click okay.
  Click green start arrow to start our virtual machine >> install ubuntu >> english >> normal installation and download updated as checked >> erase disk and install ubuntu >> continue >> select location >> create account >> continue >> finish >> resatart >> enter >> login screen with the password >> skip all >> done.
  For latest, updated version click on Activities >>  type software update >> find the gray icon with the A on it and install now >> OK.
  Go to top right of the screen click the downward facing arrow >> choose the power off>> power off>> restart>> login again user name and password.
  Activities >> type "terminal" >> sudo apt install gcc make perl >> password >> Y >> close it. 
  Go to up to VirtualBox >> devices >> insert guest adm CD image >> run >> password >> close it. 
  Go to top right of the screen click the downward facing arrow AGAIN >> choose the power off>> power off>> restart>> login again user name and password >> ANYMORE Virtual machine is READY. 
  Check the "View" and find the "Auto resize Guest Display" if its there, its okay. 
  Find CD image down below >> right click >> choose "eject". 

Virtual machine is ready, şimdi internete girip (firefox) githubta bu eğitimin olduğu klasörden code sekmesinden verisetlerini bu virtuall machine indir. extract et ve hazırsın.

Ben Githubcodes kullanacağım. 
Githubcodespaces is a Linux system in the Cloud. Same bash shell with Ubuntu desktop. there are some minor differences between VirtualBox and Githubcodespaces like user-home-directory or use of superuser-privileges etc. and we cant open graphical apps Githubcodespaces. but its still enough to complete the challenges.

GUI: Graphical User Interface: images, financial graphics etc.
Command-Line-Interface: text base interface where we type commands and where we can see outputs of that commands on the screen. Think like, base on the texts you type on the terminal make the softwares and hardware can communicate.
What is Bash?
  Shell: command line interpreter: terminal. One of the Shell is Bash. Widely use shell on the linux system. 
  Bash is available on Windows through  "Windows Subsystem for Linux". 
  Linux's shell(terminal means shell runs inside of a Terminal but its okay to use them interchangeably) is Bash.

  Commands on the Bash:
    command + with option/s + options with argument/s. They are short. 
    For instance intead of saying "list the file in the machine", we just type "ls", its just because "efficiency".
  when you need all the commands and its options just find the documentation, no need to take a note of all.  
pythondaki (help) neuse CLI Bash'te "man" o. 
>> man ls returns all information about "ls" command.
>> ls --help also.
>> or just help

what does the command statmyfile.txt, df -h / do? answer: man stat and man df
which command for search for files in a directory hierarhy? answer: apropos "search for files" or without ""

