[Contents](../personal_learning_record/personal_learning_record.md) | [Segment 2 - Languages and OS](../personal_learning_record/segment2.md) 

# Segment 2 - Languages and Operating Systems

---
**NOTE**

For each of the sessions, bullet point notes on what you have learnt.
Use markdown references and / or links to resources you have used
use  screen shots and / or code samples as appropriate.

---

## session 5

Session 5 was primarily about computer languages


ARM assembler and C programming using CPUlator:

CPUlator is a free cpu simulator made for teaching use, made by henry wong

CPUlator can run inside a web browser, the simulation allows running and debugging programs without needing a hardware board.

CPUlator can be used to simulate an ARM 7 processor which is similar to the processor used in a raspberry pi

On the left panel of CPUlator are the ARMv7 registers

The ARM architecture has 16 32-bit general purpose registers for use with software

R0-R14 can be used for any purpose

R13 (SP) is a stack pointer so it always points to the next available free space on the memory stack

R14 (LR) is a link register so it is used to hold the return address for a function call

R15 (PC) is a program counter so it's value is altered as the core executes instructions

On the right panel is a representation of each of the peripherals

each peripheral has a different address range and it is controlled by saving bytes into the registers within the address range

in the editor window code can be typed to produce different results

in an exercise I pasted a hello world program written in C into the editor window


Coding languages:

In this session we also learnt what machine/assembly code

Assembly code is a low level language

An assembler is a program that translates assembler source code into machine code

Assembly code is specific to each processor and is designed to make it easier for programmers to specify various instructions

High level languages include languages like C, Python and Java

High level languages are translated into low level machine code

Node red which I previously used to make the LED attached to a raspberry pi light up is considered a no code language as it is visually programmed

## session 6

Session 6 was mainly focused on operating systems and how they work

An OS manages computer hardware and software recources.

The OS manages the CPU so that time is shared across multiple processes making it look like multi tasking

The scheduler is a process that holds a table of all the processes in the system and responds to the system clock and other interrupts

The scheduler decides which process should run after a system clock interrupt occurs.

the flow of program execution for each process is called a thread

most computers now have multiple cpu cores

each core can have a thread running on it so if you had 8 core you could have 8 threads running in parallel

Virtual memory is used on disk drives so that the computer can operate as if it seemingly had infinite amounts of RAM

Virtual memory was used because RAM is a lot more expensive compared to disk drives which have much slower memory

Memory management using swapping is an essential task performed by the operating system

On something like a rasberry pi frequently using the swap file is to be avoided as the rasberry pi runs on an SD card making it's life significantly shorter if it is written to constantly.

Scheduling and memory managment are processes shared across all users of the system, these processes are called kernel processes because they are extremely important to the system and run with special privileges allowing acces to all of the memory in the system

On the other hand user processes run outside of the kernel and the parts of the system they can access are controlled closely by the kernel


## session 7

Session 7 was heavily focused on the history of the linux operating system

Linux Origins:

In the 1970s AT&T developed the original C programming language and wrote a new operating system called Unix

Compter manufacturers began developing their own variants

The "POSIX Compliant Unix standard" standardised the system calls across unix systems so that various programs could run across all variants of unix

Richard Stallman started development on a new open source unix like operating system which would be free for anyone to use, he also developed the gcc compiler and various other software utilities, he then published the software under the "copy left GPL licence" which forced people who used the source code to publish their work under the same licence

The first linux prototypes were released in late 1991 and version 1.0 was released in 1994

Linux has grown to be the major operating system powering the internet and the cloud



Linux OS structure:

Linux gives many choices as to which libraries are used to provide services in any particular layer, this makes a linux based system a lot more flexible than a windows system

The kernel provides the core operating system services including the device drivers, file systems and scheduler.

File permissions are a core part of the security model used by linus systems

File permissions dictate who can read/write to files and directories on a system

If it is a system file the owner can be root

All files have an owner, when you create one you are automatically assigned as the owner

Users can also be grouped so that the permissions can be spread across one another

UNIX systems originally had a simple ASCII terminal based user interface however after 1987 unix and linux operating systems have been using the X window system for their GUI

The boot process starts an operating system by setting up essential processes and data structures

The BIOS on PC motherboards handles diagnostics, hardware configuration and finds the boot loader on disks

Raspberry Pi lacks a BIOS so it uses a unique boot process where it starts from an SD card via the GPU


## session 8 (consolidate)

In session 8 I went back over the material in session 7 primarily as I wanted to gain a better understanding of how the Linux operating system worked

I had a look at the key shell commands and how they could be used in the terminal

I also looked further into the file permissions in Linux and how the ownership and permissions list looks when you list it in the terminal

I then did my own research on wayland and how it's replacing the X11 window system protocol in later raspberry pi's (Websites I looked at: https://www.tuxedocomputers.com/en/Whats-the-deal-with-X11-and-Wayland-_1.tuxedo    https://askubuntu.com/questions/11537/why-is-wayland-better    https://www.howtogeek.com/900698/what-is-wayland-on-linux-and-how-is-it-different-from-x/  )

