# BRUTATOS: Stage 1 Project Plan and Task List

| | |
| --- | --- |
| Course | Artificial Intelligence and Computational Science |
| Team | BRUTATOS |
| Project module | Hardware, Networks & Behaviorist AI |
| GitHub repository | https://github.com/GaloNr/BIT-CSE11001-BRUTATOS |
| Task list (live version) | TASKLIST.md in the repository above, plus our Trello board |
| Document version | v1.0, Stage 1 submission (deadline October 24, 2026, 23:59 Beijing time) |
| Submission lead | Rassul |

This is our working plan. We will keep updating it in the repository after we submit it, and every change will be visible in the commit history.

<br> 

## A. Team information and responsibilities

We are six people, and each of us has three jobs: one coordination role, one production deliverable to lead, and one part of the content to research and write. Nobody only "manages" and nobody only "writes".

### Members

| Name (as on class roster) | Chinese name | Student ID | Role | Strengths and experience | Skills to develop |
| --- | --- | --- | --- | --- | --- |
| Mussaldinov Rassul | 苏岚 | 1820262146 | Research & Learning Lead | Has built websites with Next.js and Supabase, a Telegram bot and an iOS widget app, so Git and Markdown aren't new to him. Made Canva presentations for a workwear factory. Studies Mechanical Engineering, which helps with the robot side of Behaviorist AI | Explaining theory simply in English; talking on camera |
| Matashev Ariet | 舒尔恪 | 1820262363 | Systems & Workflow Architect | Good at organizing people and tasks; set up our Trello board for the team | Using GitHub; making slides that explain with pictures instead of walls of text |
| Ali Ahmed | 柳青 | 1820262072 | Project Manager | Likes planning and keeping things on schedule | Video editing and recording narration; writing short, clear meeting notes |
| Benslima Khalid | 韩力 | 1820262152 | Content Reviewer & Quality Assurance (QA) | Pays attention to details and notices when an explanation doesn't make sense | Checking facts against sources; giving feedback that is clear but not harsh |
| Kalbaev Beknazar | 柏克 | 1820262361 | Data Engineer | Keeps files organized and is good at finding information online | Drawing diagrams; writing good test questions with explanations |
| Karbuzov Sanzhar | 宋哲 | 1820262137 | GitHub & Markdown Manager | Picks up new tools quickly; started our GitHub setup | Reviewing other people's changes on GitHub; Markdown formatting |

### What each role means in practice

**Rassul, Research & Learning Lead.** Owns the research plan and the learning objectives: what the team needs to learn, in what order, and from which sources. Writes the learning goals and the content outline, keeps the shared glossary, checks that every section is clear and fits the learning sequence, and submits our work on the course site.

**Ariet, Systems & Workflow Architect.** Owns the project workflow and task coordination. Designs how work moves from a Markdown draft to review, then to slides, study guide and video, decides which tools we use at each step, and makes sure every task has someone working on it. He also writes the first hardware lessons.

**Ahmed, Project Manager.** Owns the project timeline, meetings, deadlines and progress tracking. Sets internal deadlines, runs the weekly meeting, writes the meeting summaries, keeps task statuses up to date and writes the project log.

**Khalid, Content Reviewer & Quality Assurance (QA).** Checks that facts, examples and answers in each section are correct and that the sources are real and support the text, before a section is marked "checked". He also checks every submission against the assignment's quality checklist before it goes in.

**Beknazar, Data Engineer.** Owns data organization and supporting materials: the shared source list, images, diagrams and the slides. Decides how files are named and stored, so everyone works with the same files and nothing gets lost.

**Sanzhar, GitHub & Markdown Manager.** Creates and maintains the repository, the [README.md](https://github.com/GaloNr/BIT-CSE11001-BRUTATOS/blob/main/README.md) and the folder structure. Sets the Markdown style rules, reviews and merges changes, and helps teammates who are new to GitHub.

### How the work is split

| Member | Coordination role | Leads this deliverable | Researches and writes |
| --- | --- | --- | --- |
| Rassul | Research plan, learning objectives, glossary, submission | Study Guide | Behaviorist AI, sections 3.4 to 3.6, and Part 4 |
| Ariet | Workflow and task coordination | Test Bank | Hardware, sections 1.1 to 1.3 |
| Ahmed | Timeline, meetings, deadlines, progress tracking, project log | Video Tutorials | Networks, sections 2.5 to 2.7 |
| Khalid | Content review, quality and source checks | Live Mini Lecture | Behaviorist AI, sections 3.1 to 3.3 |
| Beknazar | Data organization and supporting materials | PPT Slides and diagrams | Hardware, sections 1.4 to 1.7 |
| Sanzhar | GitHub and Markdown | Repository and README | Networks, sections 2.1 to 2.4 |

We split it this way so that every person writes real content, and every deliverable has one clear owner. Roles show who is responsible, not who is allowed to work on something: everyone studies all three parts, reviews other people's sections and can explain the whole project. If the load becomes uneven, we raise it at the weekly meeting and move tasks, and the change is recorded in the task list.

<br> 

## B. Project scope and learning goals

Our materials will teach a complete beginner how a computer works inside, how computers talk to each other, and how an AI can act intelligently by reacting to the world instead of reasoning about it. The three parts are linked by one running example: a small robot vacuum, which needs hardware to sense and move, a network to receive updates, and behaviorist AI to decide what to do.

### Target learners

First-year university students from any major who use computers and phones every day but have never studied computer science. We assume they can read basic English, do school-level arithmetic, and know what a file, an app and a website are. We do not assume any programming, electronics or networking knowledge. Many of our classmates study in English as a second language, so we will keep sentences short and explain every technical term the first time it appears.

### Learning goals

After using our materials, a beginner should be able to:

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

### Content outline

**Part 1. Hardware**

- 1.1 What a computer is: input, processing, storage, output
- 1.2 Bits and bytes: how numbers and text are stored in binary
- 1.3 The von Neumann architecture: CPU (control unit, ALU, registers), memory, buses, input and output
- 1.4 The fetch, decode, execute cycle
- 1.5 The memory hierarchy: registers, cache, RAM, storage
- 1.6 What makes a computer fast: clock speed, cores, cache
- 1.7 Hardware for AI and robots: GPUs, sensors and actuators

**Part 2. Networks**

- 2.1 What a network is: LAN and WAN, routers and switches
- 2.2 Packets and packet switching
- 2.3 Addresses: IP addresses, with MAC addresses and ports introduced briefly
- 2.4 Protocols and layers: the four-layer TCP/IP model
- 2.5 TCP and UDP
- 2.6 DNS and what happens when you open a website
- 2.7 The internet and the web, HTTP and HTTPS, basic network security

**Part 3. Behaviorist AI**

- 3.1 Three schools of AI: symbolism, connectionism, behaviorism
- 3.2 Roots in cybernetics: feedback loops (thermostat example)
- 3.3 Agents and environments: the sense, decide, act loop and reactive agents
- 3.4 Brooks' subsumption architecture and "intelligence without representation" (layered robot behaviors)
- 3.5 Learning from rewards: an introduction to reinforcement learning
- 3.6 Strengths and limits of behaviorist AI

**Part 4. Putting it together**

- 4.1 One system, three layers: the robot vacuum from sensor to network to decision

### Scope boundaries

| Explained in detail, with worked examples and practice | Introduced briefly, so learners know they exist |
| --- | --- |
| Von Neumann architecture (1.3) | Binary conversion beyond simple examples (1.2) |
| Fetch, decode, execute cycle (1.4) | Performance factors (1.6), GPUs (1.7) |
| Memory hierarchy (1.5) | MAC addresses and ports (2.3) |
| Packets and IP addresses (2.2, 2.3) | The OSI model (only mentioned as an alternative to TCP/IP) |
| What happens when you open a website (2.6) | HTTPS and security (2.7) |
| Reactive agents and the sense, decide, act loop (3.3) | Cybernetics history (3.2) |
| Subsumption architecture (3.4) | Reinforcement learning (3.5): the idea only, no formulas |

One thing we will confirm with the teacher early is how deep reinforcement learning (3.5) and the OSI model (2.4) should go. Until then, both stay at an introductory level.

<br> 

## C. Planned learning resources and mini lecture

All three resources are built from the same Markdown files, so a fact is written once and then reused. The study guide is for careful reading and practice, the slides show the ideas visually, and the videos cover the processes that are easier to understand when you watch them move.

| Component | Our plan |
| --- | --- |
| Shared Markdown content | One Markdown file per outline section, all written with the same template: learning goals, key terms, explanation, worked example, "try it yourself" questions with answers, common mistakes and sources. A shared glossary keeps our terms consistent. Files live in the `src/` folder of the repository. |
| Study Guide and Test Bank | The study guide follows the outline in four parts. Each section opens with its goals, explains the idea through the worked example, then ends with three to five practice questions and answers at the back. The test bank holds about 50 questions (around 15 per part plus a few for Part 4): multiple choice, short answer and "trace the steps" questions. Each question is tagged with its learning goal and difficulty (easy, medium, hard) and has an explanation, not just a letter. |
| PPT Slides | One short slide group per section, built around diagrams instead of text: a von Neumann block diagram, the fetch, decode, execute cycle shown step by step on a three-instruction program (LOAD, ADD, STORE), a memory hierarchy pyramid, a map of one packet's journey, a DNS lookup sequence, and the layers of a subsumption robot. Each part ends with two or three check questions taken from the test bank. |
| Video Tutorials | Three tutorials of 5 to 8 minutes each. (1) "Inside the CPU": the fetch, decode, execute cycle animated on a tiny program. (2) "What happens when you open a website": a screen-recorded demo using `ping`, `nslookup` and `traceroute`, with narration. (3) "A robot without a brain": a simple reactive robot built in Scratch, adding one behavior layer at a time to show subsumption. Each video ends with two quiz questions. |
| Live Mini Lecture | Proposed question: "Can a robot act smart without thinking?" It matters because it shows a completely different idea of intelligence from chatbots and neural networks, and it is the base of real products like robot vacuums. Activity: one volunteer becomes the "robot" and follows three rule cards (Layer 1: walk forward. Layer 2: if you touch an obstacle, turn right. Layer 3: if the "battery" card is shown, go to the charger). The audience places bags as obstacles and predicts what the robot will do. Simple rules produce behavior that looks planned. Backup topic: "How does a CPU run one instruction?", with students acting as the control unit, ALU and memory. We will confirm that our topic is on the topic menu before preparing it. |

**How the pieces support each other.** The Markdown is the single source, so the study guide, slides and videos always say the same thing in the same words. The test bank questions are reused at the end of slide groups and videos, so learners practise the same ideas in every format. The mini lecture tests our Part 3 material on a real audience early, and what confuses them goes back into the Markdown before the final versions.

<br> 

## D. Workflow, schedule and coordination

Nothing goes into slides or videos until its Markdown has been reviewed. Internal deadlines sit before the real ones (a few hours before for the October 24 submissions, one to three days before for later ones), so there is always time to fix things.

### How we study the content

- In the first week everyone reads the course materials for all three parts, not only their own, so we share the same basic picture.
- Each author then goes deeper on their own sections, using at least two reliable sources per section (course materials, textbooks, university or official documentation).
- At every weekly meeting each author gives a 3-minute "teach-back" of their section. If the others cannot follow it, the explanation is not ready yet.

### How Markdown is written and checked

1. The author finds at least two sources and writes the section using our lesson template (see the Appendix). Status: drafted.
2. The author works through every example and question themselves and checks the answers.
3. Khalid checks the facts, sources, examples and answers.
4. Rassul checks that the explanation is clear for a beginner, uses the glossary terms and fits the learning sequence.
5. The author fixes the comments and Sanzhar uploads the final version to GitHub. Status: checked. Only checked sections are used for the study guide, slides and videos.

The full step-by-step workflow, with who does what and in which tool, is in our separate workflow document.

Every content file carries one status label: **outline only**, **drafted**, **checked** or **needs revision**. A section becomes "checked" only after a reviewer has confirmed its facts, examples, answers and images, and the review outcome (what was checked, what was found, what was fixed or confirmed) is written down.

### How we use GitHub

- One repository with a fixed folder structure (shown in the Appendix) and a [README.md](https://github.com/GaloNr/BIT-CSE11001-BRUTATOS/blob/main/README.md) that names the team, module, structure and where each learning resource is.
- The task list lives in [TASKLIST.md](https://github.com/GaloNr/BIT-CSE11001-BRUTATOS/blob/main/TASKLIST.md) in the repository, and day-to-day tasks are tracked on our Trello board.
- Everyone commits from their own GitHub account where possible; if someone uploads work for another member, the commit message names the real author.
- Commit messages say what changed, for example `Add worked example to 1.2 bits and bytes`.
- Large video files are stored in a shared cloud folder, with working links in the `media/video/` folder. Personal logs never go into the repository.

### Communication and meetings

- Team group chat for quick questions and updates, every day.
- Weekly meeting on Sundays at 20:00 (about 45 minutes, in person or on Google Meet). Agenda: progress against the task list, blockers, teach-backs, next week's tasks. Ahmed runs it and writes the summary within 24 hours.
- Mid-week check-in in the chat on Wednesdays: each person writes one line on what is done and what is stuck.

### How corrections reach every deliverable

If a fact, example or answer changes, we fix the Markdown first. Then the person who found the problem lists every place the content is used: study guide, slides, video, test bank. Each owner updates their part, Khalid checks the fixes, and the change is noted in the commit history.

### Testing, rehearsal and feedback

- Every worked example and test question is solved by someone other than its author before it is used.
- Study guide sections are tried on two or three friends outside the course to see where they get lost.
- The mini lecture is rehearsed twice in front of the team, three days and one day before our class date, with the activity run in full.
- Teacher feedback after Stage 2 and audience feedback from the mini lecture are collected and turned into tasks.

### Schedule

| Dates | Checkpoint | Main work |
| --- | --- | --- |
| Oct 23 to 24 | All four Stage 1 submissions (Oct 24, 23:59) | This plan; repository with README and full module outline; sections 1.1 and 1.2 fully developed and reviewed; other sections started; project log; personal logs |
| Oct 25 to 29 | Status report ready (Oct 29) | 4-minute report built from real repository evidence, two timed rehearsals, USB folder tested; scope questions sent to the teacher by Oct 26 |
| Oct 30 | Live Status Report | Files submitted before our slot, report presented in class |
| Oct 25 to Nov 1 | All sections drafted and checked (Nov 1) | Remaining sections written, cross-reviewed and labelled "checked"; glossary complete |
| Nov 2 to 4 | First versions ready (Nov 4) | Study guide v1, slides v1, test bank v1, video scripts |
| Nov 5 to 6 | Package ready (Nov 6) | Record video drafts, rehearse mini lecture, check the full Stage 2 package |
| Nov 7 | Stage 2 submitted | Submission by Rassul |
| Nov 8 to 15 | Feedback collected (Nov 15) | Teacher, peer and audience feedback turned into tasks |
| Nov 16 to 22 | Revisions done (Nov 22) | Fix Markdown first, then update every affected resource |
| Nov 23 to 26 | Final versions ready (Nov 26) | Final videos, slides, study guide and test bank; consistency check; improvement summary |
| Nov 27 | Internal final deadline | Everyone checks the package |
| Nov 28 | Stage 3 submitted | Submission by Rassul |

The mini lecture date follows the class schedule. When it is announced, Ahmed adds it to the schedule and moves the rehearsal tasks to fit.

### Main risks

| Risk | What we will do |
| --- | --- |
| Some members are new to GitHub | Sanzhar shows everyone how to upload and edit files; everyone makes their first real change with his help |
| Behaviorist AI has fewer beginner-friendly sources than hardware or networks | Start with the course materials and Brooks' original papers, ask the teacher early, and pair the two Part 3 authors |
| Uneven workload or someone falls behind | Weekly check against the task list; tasks more than two days late are discussed at the meeting and reassigned if needed; every deliverable has a backup person |
| Videos must be re-recorded when content changes | Record only from approved scripts, and keep each video short so one fix does not mean redoing everything |
| AI-generated content is wrong or too advanced | Check every AI-assisted claim against two sources, test examples ourselves, and log the AI use (Section F) |
| Busy weeks with other courses and exams | Internal deadlines sit 1 to 3 days before real ones; urgent problems are raised in the chat the same day, not at the next meeting |
| Video files are too big to upload | Compress early, test the upload size on Nov 5, and contact the teacher before the deadline if a file is still over the limit |

<br> 

## E. Master task list

This is a snapshot from October 24, 2026. The live version is [TASKLIST.md](https://github.com/GaloNr/BIT-CSE11001-BRUTATOS/blob/main/TASKLIST.md) in the repository and our Trello board. Stage 1 is broken down in detail; later stages will be split into smaller tasks at the start of each stage. Where several people are listed, the first name is the lead.

### Stage 1: planning and content foundation (four submissions due October 24, status report October 30)

| ID | Task | Expected result | Responsible | Internal deadline | Status | Depends on |
| --- | --- | --- | --- | --- | --- | --- |
| T01 | Agree on team roles and responsibilities | Roles in Section A (first agreed at the Oct 20 meeting, updated in the Oct 24 group chat) | All | Oct 20 | Completed | |
| T02 | Collect everyone's roster name, student ID, GitHub username, strengths and skills to develop | Section A table complete; usernames ready for the README | Rassul | Oct 23 | Completed | T01 |
| T03 | Read the Shared Assignment Rules and all five Stage 1 assignment pages | Each member confirms in the chat | All | Oct 23 | Completed | |
| T04 | Define target learners, learning goals, content outline and scope | Section B | Rassul | Oct 23 | Completed | T03 |
| T05 | Draft workflow, schedule and risk plan | Section D and team workflow | Ahmed, Ariet | Oct 23 | Completed | T04 |
| T06 | Choose the mini lecture topic from the topic menu and draft the activity | Mini lecture row in Section C | Khalid, Rassul | Oct 24 | In progress | T04 |
| T07 | Create the GitHub repository and add all members | Working repository link | Sanzhar | Oct 23 | Completed | T02 |
| T08 | Set up folders and README (team, module, members, purpose, learners, structure, progress) | Repository structure as in the Appendix | Sanzhar, Beknazar | Oct 24, 12:00 | Completed | T07 |
| T09 | Write the full module outline: learning outcomes, prerequisites, topics, planned examples and activities, status label per section | Module outline in the repository | Rassul | Oct 24, 12:00 | Completed | T04, T08 |
| T10 | Fully develop 1.1 and 1.2 (what a computer is, bits and bytes): explanations, key terms, worked examples, a visual, exercises with answers, references | 1.1 and 1.2 Markdown files in `src/1-HARDWARE/` | Ariet | Oct 24, 14:00 | Completed | T08 |
| T11 | Read and adapt the drafts of 1.3 and 1.4 (von Neumann; fetch, decode, execute), ready to upload in Stage 2 | 1.3 and 1.4 drafts | Beknazar | Oct 24, 14:00 | In progress | T08 |
| T12 | Start every other section: key points, planned example and at least one source | Each section labelled "outline only" or "drafted" | All authors (see Section A) | Oct 24, 16:00 | In progress | T08 |
| T13 | Review 1.1 and 1.2: check facts against sources, solve the worked examples and activities | Written review outcome (checked, found, fixed or confirmed) | Rassul (1.1), Khalid (1.2) | Oct 24, 17:00 | Completed | T10 |
| T14 | Fix the review findings and relabel 1.1 and 1.2 as "checked" | Updated files and a commit for each fix | Ariet | Oct 24, 18:00 | Completed | T13 |
| T15 | Explain how 1.1 and 1.2 will become a study guide section, slides and a video | Short paragraph for the V1.0 submission report | Rassul, Ariet, Ahmed | Oct 24, 18:00 | Not started | T13 |
| T16 | Every member reads and approves this plan | Approval message from all six in the chat | All | Oct 24, 18:00 | Not started | T02, T04 to T06 |
| T17 | Export and submit this plan | `BRUTATOS_Stage1_ProjectPlan` submitted | Rassul | Oct 24, 21:00 | Not started | T16 |
| T18 | Write the V1.0 submission report: repository URL, snapshot date, latest commit ID, content status summary, captioned repository evidence, contributions, review outcome, next steps, AI use | Word or PDF report | Rassul, Sanzhar | Oct 24, 20:00 | Not started | T14, T15 |
| T19 | Export the Markdown content as a readable PDF, download the repository snapshot, build the ZIP, then extract it elsewhere and test it | `BRUTATOS_Stage1_GitHub_Markdown_V1.zip` | Sanzhar | Oct 24, 21:30 | Not started | T18 |
| T20 | Write the project log: dated entries, meeting summaries, labelled evidence (E1, E2...), AI-use records | `BRUTATOS_Stage1_ProjectLog` | Ahmed | Oct 24, 20:00 | In progress | |
| T21 | Agree the Stage 1 contribution scores together | Contribution table at the end of the project log | All | Oct 24, 20:30 | Not started | T20 |
| T22 | Each member writes their own personal log: project work and course learning, evidence and AI use beside each entry | One personal log per member | All | Oct 24, 18:00 | In progress | |
| T23 | Collect the personal logs into one document with a contents list, each log on a new page | `BRUTATOS_Stage1_PersonalLogs` | Rassul | Oct 24, 21:30 | Not started | T22 |
| T24 | Final check and submission of the V1.0 ZIP, project log and personal logs | Three submissions on the course site | Rassul, Khalid (final check) | Oct 24, 23:00 | Not started | T19, T21, T23 |
| T25 | Confirm with the teacher how deep 2.4 and 3.5 should go | Answers recorded in the repository | Rassul | Oct 26 | Not started | T04 |
| T26 | Prepare the Live Status Report: 4-minute script, slides with readable GitHub and Markdown screenshots, strongest example last, two timed rehearsals, USB folder tested | `BRUTATOS_Stage1_StatusReport`, submitted before our class slot | Ahmed, Khalid | Oct 29 | Not started | T24 |
| T27 | Draft the remaining sections (Hardware 1.3 to 1.7; all of Networks; all of Behaviorist AI; Part 4) | Every section labelled "drafted" | Section authors (see Section A) | Oct 31 | Not started | T12 |
| T28 | Cross-review all sections and complete the glossary | Every section labelled "checked", review outcomes recorded | Rassul, all | Nov 1 | Not started | T27 |

### Stage 2: first versions and live teaching (due November 7)

| ID | Task | Expected result | Responsible | Internal deadline | Status | Depends on |
| --- | --- | --- | --- | --- | --- | --- |
| T29 | Assemble Study Guide v1 from the Markdown | Study guide document, all four parts | Rassul, Khalid | Nov 4 | Not started | T28 |
| T30 | Write Test Bank v1 (about 50 questions with answers and explanations) | Test bank file, tagged by goal and difficulty | Ariet, all authors | Nov 4 | Not started | T28 |
| T31 | Draw the core diagrams (von Neumann, cycle, memory pyramid, packet path, DNS, subsumption layers, robot vacuum) | Image files in the repository | Beknazar, Ariet | Nov 2 | Not started | T28 |
| T32 | Build PPT Slides v1 | Slide deck covering all sections | Beknazar, Ariet | Nov 4 | Not started | T31 |
| T33 | Write and review scripts for the three video tutorials | Video scripts | Ahmed, section authors | Nov 3 | Not started | T28 |
| T34 | Record and edit the three video drafts | Three videos, 5 to 8 minutes each | Ahmed, Sanzhar, Rassul | Nov 6 | Not started | T33 |
| T35 | Prepare mini lecture slides and activity materials (rule cards) | Mini lecture slides, activity tested inside the team | Khalid, Rassul | Nov 5 or 4 days before our class date | Not started | T06, T28 |
| T36 | Two mini lecture rehearsals with feedback | Feedback notes | Khalid, all | 3 days and 1 day before our class date | Not started | T35 |
| T37 | Check the full Stage 2 package against the checklist and submit | Submission on the course site | Rassul, Khalid (final check) | Nov 6 (submit Nov 7) | Not started | T29 to T34 |

### Stage 3: review, revision and final delivery (due November 28)

| ID | Task | Expected result | Responsible | Internal deadline | Status | Depends on |
| --- | --- | --- | --- | --- | --- | --- |
| T38 | Collect teacher, peer and audience feedback | Feedback list, one task per problem | Ahmed | Nov 15 | Not started | T37 |
| T39 | Fix the Markdown, then update every affected resource | All corrections done | Section authors, Khalid | Nov 22 | Not started | T38 |
| T40 | Final versions of the three videos | Final video files | Ahmed | Nov 25 | Not started | T39 |
| T41 | Final Study Guide, Test Bank and Slides | Final documents | Rassul (guide), Ariet (test bank), Beknazar (slides) | Nov 25 | Not started | T39 |
| T42 | Write the improvement summary | What changed, why, and where to see it | Khalid, Rassul | Nov 26 | Not started | T39 |
| T43 | Final consistency check across all resources | Same terms, facts and answers everywhere | Rassul, Sanzhar | Nov 26 | Not started | T40, T41 |
| T44 | Final package check and submission | Submission on the course site | Rassul, Khalid (final check) | Nov 27 (submit Nov 28) | Not started | T42, T43 |

### Ongoing during the whole project

| ID | Task | Expected result | Responsible | Internal deadline | Status | Depends on |
| --- | --- | --- | --- | --- | --- | --- |
| T45 | Weekly meeting and summary | Summary within 24 hours | Ahmed | Every Sunday | In progress | |
| T46 | Update the project log and the task board | Log entries and current statuses | Ahmed | Every Sunday | In progress | |
| T47 | Update personal logs, including AI use | Personal log entries with evidence | All | Every Sunday | In progress | |

<br> 

## F. Submission, evidence and AI use

- **File:** `BRUTATOS_Stage1_ProjectPlan` (PDF or Word), submitted by Rassul after all six members approve it (T16, T17).
- **Repository:** https://github.com/GaloNr/BIT-CSE11001-BRUTATOS (public).
- **Task list:** the snapshot is in Section E; the live version is [TASKLIST.md](https://github.com/GaloNr/BIT-CSE11001-BRUTATOS/blob/main/TASKLIST.md) in the repository and our Trello board.
- **Logs:** the planning discussion is recorded in the project log, and each member records their own part in their personal log. Personal logs are submitted through the assignment channel, not stored in the repository.

### All Stage 1 submissions

| Assignment | What we submit | Due | Owner |
| --- | --- | --- | --- |
| Team Project Plan and Task List | `BRUTATOS_Stage1_ProjectPlan` (this document, Word or PDF) | Oct 24, 23:59 | Rassul |
| GitHub Repository and Markdown Content V1.0 | `BRUTATOS_Stage1_GitHub_Markdown_V1.zip`: submission report, Markdown snapshot with assets, rendered PDF of the content | Oct 24, 23:59 | Sanzhar builds it, Rassul submits |
| Project log and meeting summaries | `BRUTATOS_Stage1_ProjectLog` (Word or PDF, not zipped) | Oct 24, 23:59 | Ahmed writes it, Rassul submits |
| Personal Learning and Work Log | `BRUTATOS_Stage1_PersonalLogs`: all six logs in one Word or PDF, each starting on a new page | Oct 24, 23:59 | Each member writes their own; Rassul collects and submits |
| Live Status Report | `BRUTATOS_Stage1_StatusReport`: slides or MP4, plus the same folder on a USB drive | Oct 30, before our class slot | Ahmed, Khalid |

### AI use in this plan

We used Claude (Anthropic) on October 23, 2026 to get a starting draft and structure for this plan from our own decisions and the assignment page. The team checked it against the assignment checklist and made the decisions: the roles, who submits, which lessons come first, and the repository structure (Sanzhar's). Details are in the project log (record AI-1) and in Rassul's personal log.

### Quality checklist (ticked only after checking)

- [ ] Team information is complete, and every member understands their responsibilities.
- [ ] Learning goals describe what beginners should be able to explain or do.
- [ ] The content outline gives meaningful coverage at a manageable level of detail.
- [ ] The study guide, slides and videos have clear purposes and share one Markdown base.
- [ ] The mini lecture focuses on one idea and has a concrete teaching approach.
- [ ] The schedule includes content review, production, testing, feedback and revision before each deadline.
- [ ] Every task has an outcome, an owner, an internal deadline and a current status.
- [ ] The workload is realistic and balanced, with dependencies and risks considered.
- [ ] The document is easy to read, links work, and all members have reviewed it.
- [ ] Significant AI use is documented, and the team can explain and justify this plan.

## Appendix: repository structure and templates

### Repository structure

```
BIT-CSE11001-BRUTATOS/
├── README.md              # Team, module, members, purpose, learners, file locations, progress
├── PROJECTPLAN.md         # Project plan
├── TASKLIST.md            # Current task list
├── src/
│   ├── 1-HARDWARE/        # Lessons 1.1–1.7
│   ├── 2-NETWORKS/         # Lessons 2.1–2.7
│   └── 3-BEHAVIOURIST_AI/ # Lessons 3.1–3.6
└── media/
    ├── ppt/                # Presentation slides
    ├── video/              # Video tutorials and mini-lecture plans
    └── studyplan.md        # Study plan
```

Personal logs are never stored in the repository.

### Lesson template

```
# 1.1 Lesson title
Author: ... | Reviewed by: ... | Status: outline only / drafted / checked / needs revision

## After this section you can
## Start with an example
## Words you need
## Explanation
## Worked example
## Try it yourself
## Answers
## Common mistakes
## Sources
```

### Test bank question template

```
### Q1.2.1 (Goal 1, easy, multiple choice)
Question text
A) ...  B) ...  C) ...  D) ...
Answer: B
Why: one or two sentences explaining the answer and why the others are wrong.
Checked by: ...
```

### Meeting summary template

```
Meeting YYYY-MM-DD, time, place or platform
Present: ...   Absent: ...
What we needed to discuss:
Main points:
What we decided:
Who does what, by when:
```

### AI-use record template

```
AI use: YYYY-MM-DD, name, tool
Purpose: what I was trying to understand, create or fix
Key interactions: prompt and output excerpts or screenshots
Verification: how I checked it, what I kept, changed or rejected, and why
Outcome and learning: where it was used, what I contributed, what I learned
```
