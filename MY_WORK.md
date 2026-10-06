# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Reema Turki Alsaif] |
| **Student ID** | [445052085] |
| **University Email** | [445052085@std.psau.edu.sa |
| **GitHub Username** | [Reema-u] |
| **Repository Link** | [https://github.com/Reema-u/OS-Assignment1-Reema-Alsaif] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - October 3, 2026
**What I did:**  
I set up the project in VS Code, connected it to my GitHub repository, and added my student ID to `SchedulerSimulation.java`.

**Details:**  
I opened the project, connected it to GitHub, and made sure I could commit and push my changes.

**Challenges:**  
I had some difficulty setting up the GitHub connection.

**Solution:**  
I checked the GitHub connection and made sure the project was linked to my repository.

**Time spent:**  
1 hour
---

### Entry 2 - October 4, 2026
**What I did:**  
I worked on the priority feature and added the context switch counter.

**Details:**  
I added the priority getter and then added a counter to track context switches.

**Challenges:**  
I had some difficulty making the changes work correctly with the existing code.

**Solution:**  
I checked the code and tested the program after making the changes.

**Time spent:**  
3 hours
---

### Entry 3 - October 5, 2026
**What I did:**  
I added waiting time tracking and a summary to the program.

**Details:**  
I updated the code to track the waiting time for each process and display the results at the end.

**Challenges:**  
I had some difficulty tracking the waiting time correctly.

**Solution:**  
I checked the calculations and tested the program to make sure the waiting time was displayed correctly.

**Time spent:**  
2.5 hours
---

### Entry 4 - October 6–7, 2026
**What I did:**  
I answered the questions in `MY_WORK.md`.

**Details:**  
I reviewed my work and used it to answer the questions.

**Challenges:**  
Some questions required me to review my work first.

**Solution:**  
I reviewed my code and answered the questions in my own words.

**Time spent:**  
2 hours
---

### Entry 5 - [Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*
I learned that multithreading enables the execution of different tasks by utilizing separate threads. In this assignment, I got to understand the inner workings of the scheduler and the management of processes by the CPU using the Round-Robin algorithm. Moreover, through the application, I discovered the connection between the start(), sleep(), and join() methods to the thread cycle. The addition of the context switch counter allowed me to recognize the point at which a process resumes after being interrupted. Furthermore, I discovered the role of the ready queue in managing processes by allocating them equally to the CPU. Consequently, this assignment helped me learn about multithreading because I engaged with the material on the coding level.

## Question 2: What was the most challenging part of this assignment?
The most challenging aspect of this particular assignment was the opportunity to work with the provided long code. The process of going through the code and understanding the interconnections between different elements was at times overwhelming. At the same time, it was crucial to ensure that the changes made do not interfere with the general functionality, thus, testing became an integral part of the experience. Needless to say, multiple alterations had to be reviewed in order to ensure that the final result is an upgraded version compared to the original code. As such, it could be concluded that the task was highly engaging and educational, providing an invaluable insight into the production of a working program.

## Question 3: How did you overcome the challenges you faced?
I overcame the challenges by taking my time and checking my work step by step. The code was long, so I checked each part carefully. I also ran the code after making changes to make sure everything was working. When I was confused, I went back to the code and checked it again. I also checked GitHub to make sure my changes were there. In the end, checking and testing my work helped me finish the assignment.ite your answer here.

## Question 4: How can you apply multithreading concepts in real-world applications?
I can see multithreading being useful in many applications that I use every day. For example, a web browser can load a page while I am still using the browser. In a music app, one task can play the music while another handles the buttons and user actions. Games can also use different threads to handle things like player input and game actions. Mobile apps can use background threads to do some tasks without stopping the app. After working on this assignment, I understand better how multiple tasks can share the CPU and get time to run.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is a program that has its own memory, while a thread is a smaller unit that runs inside a process. Threads can share memory, so communication between them is usually easier and faster. In my assignment, the Process class represents a simulated process, but the actual execution is handled by a Java thread. In the addProcessToQueue() method, I used new Thread(process) to create a thread for each process. After that, the scheduler manages these threads using the Round-Robin algorithm.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

When P1 does not finish within the 4000ms time quantum, it gives up the CPU and goes back to the ready queue. In my output, P1 was added back to the queue two times before it finished. After the first quantum, it had 5402ms left, and after the second one, it had 1402ms left. On its next turn, P1 ran for 1402ms and finished. This re-queuing is important because it gives the other processes a chance to run instead of letting one process use the CPU for too long.

Example from my output:
1-  ▶ P1 executing quantum [4000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P1 completed quantum 4000ms │ Overall progress: [████████░░░░░░░░░░░░] 42%
     Remaining time: 5402ms
  ↻ P1 yields CPU for context switch

  ➕ P1 added to ready queue

2- ▶ P1 executing quantum [4000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P1 completed quantum 4000ms │ Overall progress: [█████████████████░░░] 85%
     Remaining time: 1402ms
  ↻ P1 yields CPU for context switch

  ➕ P1 added to ready queue 

3-  ▶ P1 executing quantum [1402ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P1 completed quantum 1402ms │ Overall progress: [████████████████████] 100%
     Remaining time: 0ms
  ✓ P1 finished execution!

**Explanation of example:**
P1 needed 9402ms to finish, while the time quantum was only 4000ms. So, P1 could not finish in one turn and had to go back to the ready queue. This happened two times, because P1 still had 5402ms after the first turn and 1402ms after the second turn. On the third turn, P1 only needed 1402ms, so it finished. This shows how Round-Robin gives other processes a chance to run too.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**:P1 is in the New state when a new Thread is created for it in addProcessToQueue() using new Thread(process).

2. **Runnable**:P1 becomes Runnable when the scheduler calls Thread.start(), so it is ready to run.

3. **Running**:P1 is Running when its thread starts executing the run() method and uses the CPU for its time quantum.

4. **Waiting**:P1's thread waits for a short time when Thread.sleep() is used inside run(), while the main thread waits for the process using Thread.join().

5. **Terminated**:P1 becomes Terminated when its run() method finishes and its remaining time reaches 0ms

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU scheduling]

**Description**:
An operating system can have many programs running at the same time. The CPU gives each program a short time to run, then moves to the next program. This is similar to my simulation, where P1 gets 4000ms and then goes back to the ready queue if it is not finished

**Why Round-Robin works well here**:
Round-Robin gives every program a fair chance to use the CPU. The time quantum gives each program a fixed time, and a context switch happens when the CPU moves to another program. This helps the system respond well when many programs are running

### Example 2: [Online Game]

**Description**:
An online game has many tasks running at the same time, such as player input and game actions. These tasks need to use the CPU to keep the game working. Round-Robin can give each task a turn, like the processes in my simulation.

**Why Round-Robin works well here**:
Round-Robin gives each task a fair chance to use the CPU. The time quantum gives each task a short time to run, and a context switch lets another task run. This can help the game respond quickly when many tasks are running

## Summary

**Key concepts I understood through these questions:**
1. Round-Robin gives each process a fair chance to use the CPU.
2. The time quantum controls how long a process can run.
3. A context switch happens when the CPU moves from one process to another.

**Concepts I need to study more:**
1. Thread states and the thread lifecycle.
2. How the CPU gives time to different processes.
---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
