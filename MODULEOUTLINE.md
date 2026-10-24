# Module outline: Hardware, Networks & Behaviorist AI

## Who this is for and what you need first

For first-year students with no computer science background. You need to:

- be comfortable with school-level arithmetic
- know what a file, an app and a website are
- read basic English (we explain every technical word the first time it shows up)

Nothing else. No programming needed.

## What you'll be able to do at the end

1. Name the main parts of a computer (CPU, memory, storage, input and output) and say what each one does.
2. Walk through the fetch, decode, execute cycle step by step for a simple instruction.
3. Explain why computers use several kinds of memory, and compare them by speed and size.
4. Describe how data travels across the internet in packets, and what IP addresses and routers do.
5. Explain what happens between typing a web address and seeing the page.
6. Explain the difference between TCP and UDP, with an everyday example of each.
7. Compare the three main schools of AI (symbolic, connectionist, behaviorist) in a sentence or two each.
8. Explain how a reactive agent works through a sense, decide, act loop, and describe Brooks' subsumption architecture with a robot example.
9. Explain the basic idea of learning from rewards (state, action, reward).
10. Use a robot vacuum to show how hardware, networks and behaviorist AI work together.

## Why the topics are in this order

We start inside one computer (Part 1), then connect computers together (Part 2), then look at machines that act on their own in the real world (Part 3). Each part needs the one before it: a robot needs hardware to sense and move, and usually a network to get updates. Part 4 puts all three together in one example.

## Sections and status

Status labels: **outline only** (key points planned), **drafted** (full text written), **checked** (reviewed by a teammate), **needs revision**.

### Part 1: Hardware

| Section | What it covers | Planned example or activity | Author | Status |
| --- | --- | --- | --- | --- |
| 1.1 What is a computer? | input, processing, storage, output | robot vacuum split into the four jobs; sort devices into the four groups | Ariet | checked |
| 1.2 Bits and bytes | binary, place values, text as numbers | 13 to binary and back; decode a binary message | Ariet | checked |
| 1.3 The von Neumann architecture | CPU, memory, buses, registers, stored-program idea | reading one number from memory; diagram; 4 questions | Ariet | outline only |
| 1.4 The fetch, decode, execute cycle | the three stages, tracing a program | full trace of a 4-instruction program; trace-it-yourself task | Beknazar | outline only |
| 1.5 The memory hierarchy | registers, cache, RAM, storage | where a game's files live | Beknazar | outline only |
| 1.6 What makes a computer fast? | clock speed, cores, cache, pipelining | compare two CPUs | Beknazar | outline only |
| 1.7 Hardware for AI and robots | GPUs, sensors, actuators | robot vacuum parts list | Beknazar | outline only |

### Part 2: Networks

| Section | What it covers | Planned example or activity | Author | Status |
| --- | --- | --- | --- | --- |
| 2.1 What is a network? | LAN, WAN, routers, switches | from our dorm to a website | Sanzhar | outline only |
| 2.2 Packets | packet switching, headers | rebuild out-of-order packets | Sanzhar | outline only |
| 2.3 IP addresses | IPv4, IPv6, MAC, ports | spot valid IP addresses | Sanzhar | outline only |
| 2.4 Protocols and layers | TCP/IP model, encapsulation | a chat message through the layers | Sanzhar | outline only |
| 2.5 TCP and UDP | reliable vs fast | pick TCP or UDP for five apps | Ahmed | outline only |
| 2.6 DNS and opening a website | DNS, request and response | nslookup and traceroute demo | Ahmed | outline only |
| 2.7 The web, HTTP and HTTPS | web vs internet, HTTPS, phishing | spot the fake website address | Ahmed | outline only |

### Part 3: Behaviorist AI

| Section | What it covers | Planned example or activity | Author | Status |
| --- | --- | --- | --- | --- |
| 3.1 Three schools of AI | symbolism, connectionism, behaviorism | sort AI examples into the schools | Khalid | outline only |
| 3.2 Cybernetics and feedback | feedback loops | thermostat step by step | Khalid | outline only |
| 3.3 Agents and environments | sense, decide, act; reactive agents | rules for the vacuum world | Khalid | outline only |
| 3.4 Subsumption architecture | Brooks' layered robots | predict the robot's moves | Rassul | outline only |
| 3.5 Learning from rewards | state, action, reward | best path on a reward grid | Rassul | outline only |
| 3.6 Strengths and limits | what it's good and bad at | does behaviorist AI fit this task? | Rassul | outline only |

### Part 4: Putting it together

| Section | What it covers | Planned example or activity | Author | Status |
| --- | --- | --- | --- | --- |
| 4.1 The robot vacuum | all three parts in one system | label the robot diagram | Rassul | outline only |

## Gaps and open questions

- 1.1 and 1.2 are checked (reviewed by Rassul and Khalid on 24 October).
- 19 sections are outline only. Target: all drafted by 31 October, all checked by 1 November.
- We still need to check with the teacher how deep to go on reinforcement learning (3.5) and whether the OSI model is needed (2.4). For now both stay at an intro level.
- Good beginner-level sources for Part 3 are harder to find than for Parts 1 and 2, so we start from the course materials and Brooks' original papers.
