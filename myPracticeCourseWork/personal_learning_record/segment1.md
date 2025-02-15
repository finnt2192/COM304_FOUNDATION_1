[Contents](../personal_learning_record/personal_learning_record.md) | [Segment 1 - computer Arch](../personal_learning_record/segment1.md) 

# Segment 1 - Computer Architecture

---
**NOTE**

For each of the sessions, bullet point notes on what you have learnt.
Use markdown references and / or links to resources you have used
use  screen shots and / or code samples as appropriate.

---

## session 1
In session one I learnt about the history of computing

I learnt about some important people who are relevant to mechanical computing:

Charles Babbage (1791–1871)

British mathematician, known as the father of computers

Inventor of the Difference Engine

The Difference Engine is considered a key piece of computing history

Ada Lovelace (1815–1852)

Full name: Augusta Ada King, Countess of Lovelace

Regarded as the first computer programmer

Had a long working relationship and friendship with Charles Babbage


I also learnt about the importance of analog computers:

Analog computers laid the groundwork for modern computing techniques and helped solve complex mathematical problems in a time where digital computers were unable to.




Digital computers:

George Boole Jnr is the creator of Boolean algebra which is extremely important to modern computing

Boolean algebra enables logical decision making in machines

Alan Turing invented the bombe which was used to decode enigma in WW2 through a brute force attack

He also invented the Turing machine which had all the core concepts of the modern computer, it was a model of a CPU


Electronic computers:

Colossus (made in 1943) was the first programmable computer, It was designed to decode the Lorenz cipher

ENIAC (electronic numerical integrator and computer) was the first programmable electronic digital computer, made with 18000 vacuum tubes however several burned out almost every day

Transistors:

The transistor was invented at Bell Laboratories in 1947.

The worlds first transistor computer was built at the university of Manchester in November 1953

Early short term memory examples:

1955 magnetic core memory

1964 SRAM

1970 DRAM

1970 ROM

1971 EPROM


Early long term memory examples:

Punched tape

Punched cards

Drum

Disk IBM350 3.75mb

Tape


Atlas computer:

The atlas computer was one of the worlds first supercomputers

In 1962 it was claimed to be the most powerful computer in the world (at the time)

It introduced multiprogramming, Job scheduling, Spooling, Interrupts, Pipelining, Interleaved storage, Virtual storage, Paging and Autonomous transfer units



During this session I also started to learn how git works and created an account on GitHub so that I could create the personal learning diary, I also learnt how to clone a repository.



## session 2

Session 2 was focused on computer architecture


Classic von-neumman architecture components:

A processing unit with both an arithmetic logic unit and processor registers

A control unit that includes an instruction register and a program counter

memory that stores data and instructions 

external mass storage

input and output mechanisms

Diagrams used in slideshow: https://imgur.com/a/IGfDiFO  https://imgur.com/a/G1vjyqB


Types of memory on cpu:

Registers

Arithmetic logic unit

Layer 1 cache

Layer 2 cache

Memory management unit

comparing or processing memory in registers is very fast

hitting caches may be a lot slower


Types of memory off cpu:

SRAM/DRAM

disk - HDD / SSD

Removable - Floppy disk / SD card / Tape

Virtual memory



I also learnt about the differnces between X86 and ARM Architecture

These differnces include:

x86 consumes more power

ARM is better for simple tasks however x86 is better for more complex tasks

x86 is found in most desktop computers and laptops but ARM is found more in mobile devices

I also got to learn about the rasberry pi through diagrams of it's hardware.

Diagrams shown in slideshow: https://imgur.com/a/LI27N7b      https://imgur.com/a/4pJ7Qhg



During this session I also learnt how to clone a github repo onto my pc and then merge it with newer branches.

## session 3

In this session I looked deeper into the architecture of the raspberry pi

the GPIO unit on a pi is connected to the 40 pin connector.

Programming the GPIO can be complex but it can be made simpler with many of the tools and libraries that are available to make it easier for a user without having to understand the complexity of the GPIO

In this session I learnt how to wire an LED into a raspberry pi so that it can be used with node red, then I downloaded Node red onto a raspberry pi in order to control LED lights and have them form a traffic light pattern.


## session 4 (consolidate)

In this session I mainly wanted to go back and go over what information I had already learnt from previous sessions.

I spent some time looking at the slideshows that had been used in previous sessions to remember anything I had missed while I was in class. I picked up a lot of information from the history of computing slideshow that was shown to me in session 1. I also looked deeper at the structure of the rasberry pi and how it worked, I also took a look at the specifications of the pi 3 to see what it's limitations were.

I also decided to take a second look at the GPIO Pinout diagram to further understand what each pin is used for and what it does because when I was first trying to get the LED to work I just followed the instructions given to me without really understanding why I should be putting the cathode and anode of the LED in that specific spot.
