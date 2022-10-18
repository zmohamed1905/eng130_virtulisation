
https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v


# Vagrant

- Vagrant ssh to get into vm
- read a folder- cat filename
- check internet conectivity - sudo apt-get update
- run upgrade - sudo apt-get-upgrade - y
- locating where you are - pwd
- whoami- - folder name, uname - gives OS used in vm or uname- a - version of OS you are using

Creating a file in Linux:
- check files available in current location- ls
- navigate to folder cd folder name

How to navigate out of folder = cd folder name
how to delete a folder = rm -rf filename
- copy file from 1 location to another 
- for admin access = sudo and to switch to admin user = sudo su
- change permissions chmod instruction filename
- how to delete a folder/hidden folder = la-a

# Tast

- print first 3 lines from the test.txt - head -3 text.txt
- print last 10 lines from the test.txt- tail -10 text.txt
- print last lines from the test.txt -tail -1 text.txt

# Pipe, Grep and Sort
- Pipe = sends the output of one command to another command
- Grep = allows you to find a word by searching through all texts in a file
- Sort = sorts the contents of a text file, line by line
- ps aux--sort user

# Task
What is virtualisation & benefits of it?
- Virtualization relies on software to simulate hardware functionality and create a virtual computer system. 
- This enables IT organizations to run more than one virtual system – and multiple operating systems and applications – on a single server. The resulting benefits include economies of scale and greater efficiency.

What is dev env?
- A development environment in software and web development is a workspace for developers to make changes without breaking anything in a live environment.

What is vagrant?
- Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time

What is a virtual box?
- VirtualBox is open-source software for virtualizing the x86 computing architecture. 
- It acts as a hypervisor, creating a VM (virtual machine) where the user can run another OS (operating system).

# How to force kill process in Linus:



- Use the pidof command to find the process ID of a running program or app

  `pidoff appname`



- To kill process in Linux with PID:

  `kill -9 pid`



- Want to kill process in Linux with application name? Use:

  `killall -9 appname`
