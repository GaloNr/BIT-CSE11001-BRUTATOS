# Module outline: Hardware, Networks & Behaviorist AI

Team BRUTATOS. Version 2.0 (Stage 2), 5 November 2026.

## Who this is for and what you need first

For first-year students with no computer science background. You need to:

- be comfortable with school-level arithmetic
- know what a file, an app and a website are
- read basic English (we explain every technical word the first time it shows up; see [GLOSSARY.md](GLOSSARY.md))

Nothing else. No programming needed.

## What you'll be able to do at the end

1. Name the main parts of a computer (CPU, memory, storage, input and output) and say what each one does. (1.1, 1.3)
2. Walk through the fetch, decode, execute cycle step by step for a simple instruction. (1.4)
3. Explain why computers use several kinds of memory, and compare them by speed and size. (1.5)
4. Describe how data travels across the internet in packets, and what IP addresses and routers do. (2.1 to 2.3)
5. Explain what happens between typing a web address and seeing the page. (2.4, 2.6, 2.7)
6. Explain the difference between TCP and UDP, with an everyday example of each. (2.5)
7. Compare the three main schools of AI (symbolic, connectionist, behaviorist) in a sentence or two each. (3.1)
8. Explain how a reactive agent works through a sense, decide, act loop, and describe Brooks' subsumption architecture with a robot example. (3.2 to 3.4)
9. Explain the basic idea of learning from rewards (state, action, reward). (3.5)
10. Use a robot vacuum to show how hardware, networks and behaviorist AI work together. (3.6, 4.1)

## Why the topics are in this order

We start inside one computer (Part 1), then connect computers together (Part 2), then look at machines that act on their own in the real world (Part 3). Each part needs the one before it: a robot needs hardware to sense and move, and usually a network to get commands and updates. Part 4 puts all three together. One running example, **Dusty the robot vacuum**, appears in every section. A suggested weekly route is in [media/studyplan.md](media/studyplan.md).

## How every section is built

Each file uses the same template: After this section you can; Start with an example; Words you need; Explanation (with at least one diagram or table); Worked example; Try it yourself (including tracing, predicting, comparing or finding an error, not only recall); Answers; Common mistakes; Sources.

## Sections, authors, reviewers and status

Status labels: **outline only**, **drafted** (full text written), **checked** (reviewed by a teammate who is not the author), **needs revision**. Every section is also checked for clarity and sequence by Rassul (Research & Learning Lead); Khalid (QA) is the main fact checker.

### Part 1: Hardware

| Section | File | What it covers | Main example or activity | Author | Reviewer | Status |
| --- | --- | --- | --- | --- | --- | --- |
| 1.1 What is a computer? | [1-1-what-is-a-computer.md](src/1-HARDWARE/1-1-what-is-a-computer.md) | input, processing, storage, output; hardware and software | Dusty's four jobs; find the error; predict a broken sensor | Ariet | Rassul | checked |
| 1.2 Bits and bytes | [1-2-bits-and-bytes.md](src/1-HARDWARE/1-2-bits-and-bytes.md) | binary, place values, ASCII, a map stored as bits | 13 to binary and back; decode HI; read Dusty's map row | Ariet | Khalid | checked |
| 1.3 The von Neumann architecture | [1-3-von-neumann-architecture.md](src/1-HARDWARE/1-3-von-neumann-architecture.md) | CPU (control unit, ALU, registers), memory, buses, stored program | read one number from memory; trace a write | Ariet | Khalid | checked |
| 1.4 The fetch, decode, execute cycle | [1-4-fetch-decode-execute.md](src/1-HARDWARE/1-4-fetch-decode-execute.md) | PC, IR, ACC; tracing a program | full trace of LOAD/ADD/STORE/HALT; predict; optional Little Man Computer | Beknazar | Ariet | checked |
| 1.5 The memory hierarchy | [1-5-memory-hierarchy.md](src/1-HARDWARE/1-5-memory-hierarchy.md) | registers, cache, RAM, storage; volatile | where a game's files live; stretched access times | Beknazar | Ariet | checked |
| 1.6 What makes a computer fast? | [1-6-what-makes-a-computer-fast.md](src/1-HARDWARE/1-6-what-makes-a-computer-fast.md) | clock speed, cores, cache, pipelining (brief) | compare two CPUs for two tasks | Beknazar | Khalid | checked |
| 1.7 Hardware for AI and robots | [1-7-hardware-for-ai-and-robots.md](src/1-HARDWARE/1-7-hardware-for-ai-and-robots.md) | sensors, actuators, microcontrollers, GPUs | Dusty's parts list; design a carpet behavior | Beknazar | Rassul | checked |

### Part 2: Networks

| Section | File | What it covers | Main example or activity | Author | Reviewer | Status |
| --- | --- | --- | --- | --- | --- | --- |
| 2.1 What is a network? | [2-1-what-is-a-network.md](src/2-NETWORKS/2-1-what-is-a-network.md) | LAN, WAN, switches, routers, ISP | from the dorm to a website; phone on 4G to Dusty | Sanzhar | Ahmed | checked |
| 2.2 Packets | [2-2-packets.md](src/2-NETWORKS/2-2-packets.md) | packet switching, headers, sequence numbers | rebuild out-of-order packets; count packets | Sanzhar | Ahmed | checked |
| 2.3 IP addresses | [2-3-ip-addresses.md](src/2-NETWORKS/2-3-ip-addresses.md) | IPv4 as 4 bytes, IPv6, private addresses, MAC, ports | spot valid IP addresses | Sanzhar | Khalid | checked |
| 2.4 Protocols and layers | [2-4-protocols-and-layers.md](src/2-NETWORKS/2-4-protocols-and-layers.md) | TCP/IP model, encapsulation; OSI mentioned only | Dusty receives PAUSE through the layers | Sanzhar | Khalid | checked |
| 2.5 TCP and UDP | [2-5-tcp-and-udp.md](src/2-NETWORKS/2-5-tcp-and-udp.md) | handshake, ACK, resending; reliable vs fast | pick TCP or UDP for five apps; firmware vs live video | Ahmed | Sanzhar | checked |
| 2.6 DNS and opening a website | [2-6-dns-and-opening-a-website.md](src/2-NETWORKS/2-6-dns-and-opening-a-website.md) | DNS lookup, cache, request and response | nslookup, ping and traceroute demo; order the steps | Ahmed | Sanzhar | checked |
| 2.7 The web, HTTP and HTTPS | [2-7-web-http-https.md](src/2-NETWORKS/2-7-web-http-https.md) | web vs internet, status codes, HTTPS, phishing | spot the fake website address | Ahmed | Khalid | checked |

### Part 3: Behaviorist AI

| Section | File | What it covers | Main example or activity | Author | Reviewer | Status |
| --- | --- | --- | --- | --- | --- | --- |
| 3.1 Three schools of AI | [3-1-three-schools-of-ai.md](src/3-BEHAVIOURIST_AI/3-1-three-schools-of-ai.md) | symbolism, connectionism, behaviorism | sort AI examples; three ways to avoid stairs | Khalid | Rassul | checked |
| 3.2 Cybernetics and feedback | [3-2-cybernetics-and-feedback.md](src/3-BEHAVIOURIST_AI/3-2-cybernetics-and-feedback.md) | feedback loops, negative and positive feedback | thermostat trace; Dusty wall following | Khalid | Rassul | checked |
| 3.3 Agents and environments | [3-3-agents-and-environments.md](src/3-BEHAVIOURIST_AI/3-3-agents-and-environments.md) | sense, decide, act; reactive agents; condition-action rules | vacuum-world trace; find the rule-order error | Khalid | Rassul | checked |
| 3.4 Subsumption architecture | [3-4-subsumption-architecture.md](src/3-BEHAVIOURIST_AI/3-4-subsumption-architecture.md) | Brooks's layered behaviors; intelligence without representation | predict who controls the wheels; add a behavior | Rassul | Khalid | checked |
| 3.5 Learning from rewards | [3-5-learning-from-rewards.md](src/3-BEHAVIOURIST_AI/3-5-learning-from-rewards.md) | state, action, reward, policy (idea only) | best path on a reward grid; find a reward-design problem | Rassul | Khalid | checked |
| 3.6 Strengths and limits | [3-6-strengths-and-limits.md](src/3-BEHAVIOURIST_AI/3-6-strengths-and-limits.md) | strengths, limits, emergence, hybrid systems | narrow-gap trap; does behaviorist AI fit this task? | Rassul | Beknazar | checked |

### Part 4: Putting it together

| Section | File | What it covers | Main example or activity | Author | Reviewer | Status |
| --- | --- | --- | --- | --- | --- | --- |
| 4.1 The robot vacuum | [4-1-the-robot-vacuum.md](src/4-PUTTING_IT_TOGETHER/4-1-the-robot-vacuum.md) | all three parts in one system | journey of the Start command; trace a surprising moment; find the errors | Rassul | Beknazar | checked |

## Scope decisions

- **3.5 Learning from rewards** stays at the level of the idea (state, action, reward, policy, worked numbers on a grid). No formulas.
- **2.4 Protocols and layers** teaches the four-layer TCP/IP model; the OSI model is only mentioned.
- Both decisions follow our Stage 1 plan. We have not yet received the teacher's answer on the depth of these two topics (task T25); if the answer differs, we will adjust in Stage 3.

## Gaps and open questions

- All 21 core sections contain full learning content, activities and checked answers.
- Diagrams are simple team-made figures (media/images). They can be improved visually in Stage 3, for example with photos of a real robot vacuum.
- Selected activities still need testing by learners outside the team (planned for Stage 3 together with the study guide).
