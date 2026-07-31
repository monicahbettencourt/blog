---
date: '2026-07-31T20:12:21+01:00'
draft: false 
title: 'Practice at the Keyboard From Day One'
tags: ["Linux", "CLI", "learning"]
---
As a child, I learned to play the piano. I had a knowledgeable and demanding teacher who lived at the top of my street, so I couldn't make excuses not to go to lessons. It's not that I didn't enjoy it (I eventually did), but in the beginning it felt tough as a 5-year-old. 

Learning musical theory first, and not being able to touch the keyboard until further along, it wasn't much fun I thought. Later on, as I learned how to play other musical instruments at school, I was thankful that my teacher insisted on learning the fundamentals first. 

I could easily adapt to new types of instruments, after learning how they functioned.

I'm now on a journey into DevOps, with a deep focus on working at the command line and learning how to use the tools available in almost all Linux-based systems first. 

The following are some of the concepts I've been learning about lately.

## The Linux Kernel, the User, and the Shell

I recently revisited the relationship between the Linux kernel, the user, and the shell.

The kernel is a program that sits at the core of the operating system, in charge of everything.

It performs many tasks, such as:

- Selection of which processes are allowed to use the CPU
- Memory allocation and management
- Hardware control
- Networking
- File management
- Process management

The user, as the name implies, wants to access the machine's resources to perform the desired tasks. But there's a problem. The kernel doesn't understand human language, and the user doesn't understand the kernel's language either (system calls, used by processes to communicate with the kernel).

This problem is solved with an intermediary (or translator) to establish the much-needed communication channel between the two parties.

The shell is a program that receives inputs through keyboard commands, mediating the communication between the user and the system, accessible through a terminal emulator.

The process goes as follows: 

User inputs commands -> Shell accepts and transmits -> Kernel performs tasks -> Shell receives results and presents -> User receives them in the terminal emulator.

The default shell program in the majority of Linux-based systems is `bash` (Bourne Again Shell), and the commands it accepts from the user are actually programs themselves. This was a surprising thing for me to have learned a few months ago. 

## The Commands That Helped Me Dive Into Linux 

In my early days of using Ubuntu Desktop, around 2021, I developed the habit of always updating software through the command line interface (CLI). This was the winning argument that convinced me to experiment with Linux, so I was invested in it, and used the following commnads:


```
sudo apt update && sudo apt upgrade && sudo snap refresh
```


For many months, I didn't entirely understand all the components of these commands. I knew that "sudo" was required to perform system updates as an administrator. But at that time, I was really focused on learning how to use this new operating system, its tools, and adopting the open-source office suite to use for my work.

Was this best practice? Maybe not. But I trusted the person who taught me. He'd insisted that I try Linux for months, and it wasn't something I'd copied from a website.

This habit became a lifeline, something that I held on to until I had time to research what Linux really is, what it's used for, and its significance to open-source software and user freedom. 

I am forever grateful to my first mentor, Jose P., for teaching me those commands. And I'm glad I accepted his challenge to try Ubuntu.  

## Conclusion

After learning and experimenting with hardware, Linux and command line fundamentals are the subjects of my first deep dive into the software layer of a computing system.

Unlike my childhood's piano lessons, this time around I've adopted a learning approach from someone who advocates mastering the fundamentals first, while developing practice sessions from day one.

Both at the piano and at the keyboard, the more we practice the faster and more agile our hands will become.

