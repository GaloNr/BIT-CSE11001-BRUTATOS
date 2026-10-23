

# Project Plan
| Course Name | Artificial Intelligence and Computational Science |
|--|--|
|Team Name| BRUTATOS|
|Project Module| Hardware, Networks & Behaviorist AI|
|Task list (live version)|[TASKLIST.md](https://github.com/GaloNr/BIT-CSE11001-BRUTATOS/blob/main/TASKLIST.md)|
|Document Version|v1.0, Stage 1 submission (deadline October 24, 2026, 23:59 Beijing time)|
|Submission Lead | Benslima Khalid 韩力 |


## **A. Team information and responsibilities**

We are six people, and each of us has three jobs: one coordination role, one production deliverable to lead, and one part of the content to research and write. Nobody only "manages" and nobody only "writes".
| Name | ID |Role |
|--|--|--|
|Rassul Mussaldinov 苏岚 | 1820262146 | Research & Learning Lead |
|Matashev Ariet 舒尔恪|1820262363|Systems & Workflow Architect|
|Ahmed Ali 柳青|1820262072| Project Manager (schedule and meetings)|
|Benslima Khalid 韩力|1820262152|Project Manager (tasks, quality and submission)|
|Kalbaev Beknazar 柏克|1820262361|Data Engineer|
|Karbuzov Sanzhar 宋哲|1820262137|GitHub & Markdown Editor|

<br>

| Name | Strengths and experience | Skills to develop |
|--|--|--|
|Rassul Mussaldinov 苏岚 |Web development (Next.js, Supabase), so already uses Git and writes in Markdown; studies Mechanical Engineering, which connects well to robots and sensors in Behaviorist AI|Explaining theory to beginners in simple English; speaking on video|
|Matashev Ariet 舒尔恪|TBD|TBD|
|Ahmed Ali 柳青|TBD|TBD|
|Benslima Khalid 韩力|TBD|TBD|
|Kalbaev Beknazar 柏克|TBD|TBD|
|Karbuzov Sanzhar 宋哲|Python programming language (data and signal processing); moderate experience with Git version control and Markdown language; Mechanical Engineering student|Coordinate team submissions to git repo; review material and pull requests|

<br>

**What each role means in practice**

>**Rassul, Research & Learning Lead.** Owns the study plan: what the team needs to learn, in what order, and from which sources. Writes the learning goals and content outline, keeps the shared glossary, and does the final accuracy and consistency check on every Markdown section before it goes into production.

>**Ariet, Systems & Workflow Architect.** Designs how work moves from an idea to a finished resource: Markdown draft, review, then slides, study guide and video. Decides which tools we use at each step and what a section must contain before it is handed over (our "definition of done").

>**Ahmed, Project Manager (schedule and meetings).** Owns the meeting timeline. Sets the weekly meeting, plans checkpoints and internal deadlines, runs the meetings and writes the meeting summaries.

>**Khalid, Project Manager (tasks, quality and submission).** Keeps the master task list and its statuses up to date, writes the project log, checks every submission against the assignment's quality checklist and is our submission lead.

>**Beknazar, Data Engineer.** In our project the "data" is everything we collect and reuse: sources, images, diagrams, test questions and large video files. He decides how these are collected, named, stored and versioned, so everyone works with the same files and nothing gets lost.

>**Sanzhar, GitHub & Markdown Manager.** Creates and maintains the repository, the README and the folder structure. Sets the Markdown style rules, reviews and merges pull requests, keeps the GitHub Projects board in sync, and helps teammates who are new to GitHub.
<br>

### **How the work is split**
| Member | Coordination role | Leads this deliverable| Researches and writes |
|--|--|--|--|
| Rassul | Study plan, glossary, final content check | Study Guide| Behaviorist AI, sections 3.4 to 3.6, and Part 4|
|Ariet| Workflow and handover rules | PPT Slides|Hardware, sections 1.1 to 1.3 |
| Ahmed | Schedule and meetings |Video Tutorials |Networks, sections 2.5 to 2.7 |
| Khalid | Task list, project log, submission | Live Mini Lecture |Behaviorist AI, sections 3.1 to 3.3|
| Beknazar | Sources, assets and file versions |Test Bank | Hardware, sections 1.4 to 1.7|
| Sanzhar | GitHub and Markdown | Repository, README and TASKLIST |Networks, sections 2.1 to 2.4 |

We split it this way so that every person writes real content, and every deliverable has one clear owner. Roles show who is responsible, not who is allowed to work on something: everyone studies all three parts, reviews other people's sections and can explain the whole project. If the load becomes uneven, we raise it at the weekly meeting and move tasks, and the change is recorded in the task list.

<br>

## **B. Project scope and learning goals**

Our materials will teach a complete beginner how a computer works inside, how computers talk to each other, and how an AI can act intelligently by reacting to the world instead of reasoning about it. The three parts are linked by one running example: a small robot vacuum, which needs hardware to sense and move, a network to receive updates, and behaviorist AI to decide what to do.

### **Target learners**

First-year university students from any major who use computers and phones every day but have never studied computer science. We assume they can read basic English, do school-level arithmetic, and know what a file, an app and a website are. We do not assume any programming, electronics or networking knowledge. Many of our classmates study in English as a second language, so we will keep sentences short and explain every technical term the first time it appears.

### **Learning goals**

**After using our materials, a beginner should be able to:**

1. Name the main parts of a computer (CPU, memory, storage, input and output devices) and explain what each one does, using the von Neumann model.

2. Walk through the fetch, decode, execute cycle step by step for a simple instruction.

3. Explain why computers use a memory hierarchy and compare registers, cache, RAM and storage by speed and size.

4. Describe how data travels across the internet in packets, and what IP addresses and routers do along the way.

5. Explain what happens, step by step, between typing a web address and seeing the page (DNS lookup, connection, request, response).

6. Explain the difference between TCP and UDP and give one everyday example of each.

7. Compare the three main schools of AI (symbolic, connectionist and behaviorist) in one or two sentences each.

8. Describe how a reactive agent works through a sense, decide, act loop, and explain Rodney Brooks' subsumption architecture with a robot example.

9. Explain the basic idea of learning from rewards (state, action, reward) as a link between behaviorism and modern AI.

10. Show, using the robot vacuum, how hardware, networks and behaviorist AI work together in one real system.

### **Content outline**

**Part 1. Hardware**
```
1.1 What a computer is: input, processing, storage, output

1.2 Bits and bytes: how numbers and text are stored in binary

1.3 The von Neumann architecture: CPU (control unit, ALU, registers), memory, buses, input and output

1.4 The fetch, decode, execute cycle

1.5 The memory hierarchy: registers, cache, RAM, storage

1.6 What makes a computer fast: clock speed, cores, cache

1.7 Hardware for AI and robots: GPUs, sensors and actuators
```

<br>

**Part 2. Networks**
```
2.1 What a network is: LAN and WAN, routers and switches

2.2 Packets and packet switching

2.3 Addresses: IP addresses, with MAC addresses and ports introduced briefly

2.4 Protocols and layers: the four-layer TCP/IP model

2.5 TCP and UDP

2.6 DNS and what happens when you open a website

2.7 The internet and the web, HTTP and HTTPS, basic network security
```

<br>

**Part 3. Behaviorist AI**
```
3.1 Three schools of AI: symbolism, connectionism, behaviorism

3.2 Roots in cybernetics: feedback loops (thermostat example)

3.3 Agents and environments: the sense, decide, act loop and reactive agents

3.4 Brooks' subsumption architecture and "intelligence without representation" (layered robot behaviors)

3.5 Learning from rewards: an introduction to reinforcement learning

3.6 Strengths and limits of behaviorist AI
```
<br>

**Part 4. Putting it together**
```
4.1 One system, three layers: the robot vacuum from sensor to network to decision
```

<br>

### **Scope boundaries**
| Explained in detail, with worked examples and practice | Introduced briefly, so learners know they exist |
|--|--|
| Von Neumann architecture (1.3) | Binary conversion beyond simple examples (1.2) |
|Fetch, decode, execute cycle (1.4)| Performance factors (1.6), GPUs (1.7)|
|Memory hierarchy (1.5)|MAC addresses and ports (2.3)|
|Packets and IP addresses (2.2, 2.3)|The OSI model (only mentioned as an alternative to TCP/IP)|
|What happens when you open a website (2.6)|HTTPS and security (2.7)|
|Reactive agents and the sense, decide, act loop (3.3)|Cybernetics history (3.2)|
|Subsumption architecture (3.4)|Reinforcement learning (3.5): the idea only, no formulas	|

One thing we will confirm with the teacher early is how deep reinforcement learning (3.5) and the OSI model (2.4) should go. Until then, both stay at an introductory level.

<br>

## **C. Planned learning resources and mini lecture**

All three resources are built from the same Markdown files, so a fact is written once and then reused. The study guide is for careful reading and practice, the slides show the ideas visually, and the videos cover the processes that are easier to understand when you watch them move.
| Component | Our plan |
|--|--|
| Shared Markdown content | One Markdown file per outline section (for example 1-4-fetch-decode-execute.md), all written with the same template: learning goals, key terms, explanation, worked example, "check your understanding" questions with answers, common mistakes, sources, and a "used in" line listing where the content appears. A shared glossary.md keeps our terms consistent. Files live in the content/ folder of the repository. |
| Study Guide and Test Bank | The study guide follows the outline in four parts. Each section opens with its goals, explains the idea through the worked example, then ends with three to five practice questions and answers at the back. The test bank holds about 50 questions (around 15 per part plus a few for Part 4): multiple choice, short answer and "trace the steps" questions. Each question is tagged with its learning goal and difficulty (easy, medium, hard) and has an explanation, not just a letter. |
| PPT Slides | One short slide group per section, built around diagrams instead of text: a von Neumann block diagram, the fetch, decode, execute cycle shown step by step on a three-instruction program (LOAD, ADD, STORE), a memory hierarchy pyramid, a map of one packet's journey, a DNS lookup sequence, and the layers of a subsumption robot. Each part ends with two or three check questions taken from the test bank. |
| Video Tutorials | Three tutorials of 5 to 8 minutes each. (1) "Inside the CPU": the fetch, decode, execute cycle animated on a tiny program. (2) "What happens when you open a website": a screen-recorded demo using ping, nslookup and traceroute, with narration. (3) "A robot without a brain": a simple reactive robot built in Scratch, adding one behavior layer at a time to show subsumption. Each video ends with two quiz questions. |
| Live Mini Lecture | Proposed question: "Can a robot act smart without thinking?" It matters because it shows a completely different idea of intelligence from chatbots and neural networks, and it is the base of real products like robot vacuums. Activity: one volunteer becomes the "robot" and follows three rule cards (Layer 1: walk forward. Layer 2: if you touch an obstacle, turn right. Layer 3: if the "battery" card is shown, go to the charger). The audience places bags as obstacles and predicts what the robot will do. Simple rules produce behavior that looks planned. Backup topic: "How does a CPU run one instruction?", with students acting as the control unit, ALU and memory. We will confirm that our topic is on the topic menu before preparing it. |

<br>

**How the pieces support each other.** The Markdown is the single source, so the study guide, slides and videos always say the same thing in the same words. The test bank questions are reused at the end of slide groups and videos, so learners practise the same ideas in every format. The mini lecture tests our Part 3 material on a real audience early, and what confuses them goes back into the Markdown before the final versions.
