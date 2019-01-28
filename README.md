### This project is about creating a virtual machine that runs on Ubuntu with Vagrant
### Author: Wolf Hopkins

#### What is a Virtual Machine?
In computing, a virtual machine is an emulation of a computer system. 

#### What is Vagrant?
Vagrant is a tool for building and managing virtual machine environments in a single workflow. 
With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, 
increases production parity, and makes the "works on my machine" excuse a relic of the past. 

#### Who is the Author of Vagrant?
Mitchell Hashimoto is the author of Vagrant

#### What is Ubuntu?
Ubuntu is a complete Linux operating system, freely available with both community and professional support. 
The Ubuntu community is built on the ideas enshrined in the Ubuntu Manifesto: 
that software should be available free of charge,
that software tools should be usable by people in their local language and despite any disabilities, 
and that people should have the freedom to customize and alter their software in whatever way they see fit.

#### What does the word Ubuntu mean?
The word Ubuntu means: a quality that includes the essential human virtues; compassion and humanity.


#### How to use VM's with Vagrant?
  enter these lines of code
   '''
$ vagrant init hashicorp/precise64
$ vagrant up
   '''
  
After running the above two commands, you will have a fully running virtual machine 
in VirtualBox running Ubuntu 12.04 LTS 64-bit. You can SSH into this machine with vagrant ssh, 
and when you are done playing around, you can terminate the virtual machine with vagrant destroy.

Now imagine every project you've ever worked on being this easy to set up! With Vagrant,
vagrant up is all you need to work on any project, to install every dependency that project needs, 
and to set up any networking or synced folders, so you can continue working from the comfort of your own machine.
  
#### What does Uname do?
uname (short for unix name) is a computer program in Unix and Unix-like computer operating systems that 
prints the name, version and other details about the current machine and the operating system running on it.
  
#### What is a Zero Day?
A zero-day (also known as 0-day) vulnerability is a computer-software vulnerability that is unknown to those who 
would be interested in mitigating the vulnerability (including the vendor of the target software). 
Until the vulnerability is mitigated, hackers can exploit it to adversely affect computer programs, data, 
additional computers or a network. An exploit directed at a zero-day is called a zero-day exploit, or zero-day attack.
