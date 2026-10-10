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
| **Full Name** | [Osamah Salah BinSaeedu] |
| **Student ID** | [445052781] |
| **University Email** | 445052781@std.psau.edu.sa |
| **GitHub Username** | [OsamahBinSeaadu] |
| **Repository Link** | [https://github.com/OsamahBinSeaadu/OS-Assignment1-Starter-Osamah-Salah-BinSaeedu.git] |
 
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

### Entry 1 - [October 10, 2026, 4:30 PM]
**What I did**:  Set up GitHub, forked the starter repository and set my student ID

**Details**:
- Signed in to GitHub with my university email
- Forked `makopt/OS-Assignment1-Starter-481` and renamed it to `OS-Assignment1-Osamah-Salah-BinSaeedu`
- Checked that the repository is Public
- Cloned it in VS Code and changed `studentID` to my ID
- Ran the program one time to see the output
- Commit: `Set my student ID: [445052781]`

**Challenges**: The colors in the output looked strange (`←[36m`) when I ran it the first time.

**Solution**: I ran the program from the VS Code terminal and the colors showed correctly.

**Time spent**:40 minutes

---

### Entry 2 - [October 10, 2026, 7:00 PM]
**What I did**:Feature 1 - Process Priority

**Details**:
- Added `private int priority` to the `Process` class
- Added `priority` to the constructor and a `getPriority()` method
- In `main`, made a random priority with `1 + random.nextInt(10)` (1 to 10)
- Changed the message in `addProcessToQueue()` to show `P1 (Priority: 7) enters the ready queue`
- Commit: `Feature 1: Added priority field to Process class`

**Challenges**: After I added the new `random.nextInt(10)`, the burst times of my processes changed from my first run.

**Solution**: I understood that all values come from the same `Random` object with my ID as seed, so one more call changes the next numbers. This is normal, and the output is still the same every time I run it.

**Time spent**: 40 minutes

---

### Entry 3 - [October 10, 2026, 8:00 PM]
**What I did**: Feature 2 - Context Switch Counter

**Details**:
- Added `static int contextSwitches = 0;` in `SchedulerSimulation`
- Added `contextSwitches++` just before `currentThread.start()` in the scheduler loop
- Printed `Total context switches: X` at the end
- Commit: `Feature 2: Implemented context switch counter`


**Challenges**: I was not sure where to put the counter: inside `run()` or in the scheduler loop.

**Solution**: A context switch happens when the scheduler gives the CPU to a process, so I put it in the loop before `start()`. Then I counted the "Ready Queue" boxes in the output and the number was the same.


**Time spent**:40 minutes

---

### Entry 4 - [October 10, 2026, 9:00 PM]
**What I did**:Feature 3 - Waiting Time Tracking and summary table

**Details**:
- Added `creationTime`, `lastReadyTime` and `waitingTime` fields to `Process`
- `markReady()` saves `System.currentTimeMillis()` when the process enters the ready queue
- `startRunning()` adds `now - lastReadyTime` to `waitingTime` before the process runs
- Added a static `allProcesses` list and `printSummaryTable()` that prints Burst, Waiting and Turnaround time
- Commit: `Feature 3: Added waiting time tracking and summary table`

**Challenges**:The columns of the table were not aligned because some titles were longer than the column width.

**Solution**: I changed the widths in `String.format` (for example `%-17s` and `%-20s`) so the lines match.

**Time spent**:1 hour 5 minutes

---

### Entry 5 - [October 10, 2026, 10:00 PM]
**What I did**:Wrote the documentation in `MY_WORK.md`

**Details**:
- Ran the full program and saved the output in a text file
- Found a process that was re-queued and copied its lines for Question 2
- Wrote the reflection and the technical answers
- Commit: `Docs: Completed development log, reflection and technical answers`

**Challenges**: Question 3 (thread lifecycle) was confusing, because the main thread and the process thread are in different states at the same time.

**Solution**:I read the lecture slide about thread states again and followed P1 line by line in the code.

**Time spent**:30 minutes

---

### Entry 6 - [October 10, 2026, 10:30 PM]
**What I did**:Recorded and uploaded the demo video

**Details**:- Recorded my screen while running the program in VS Code
- Uploaded the video to Google Drive and set it to "Anyone with the link"
- Added the link to `MY_WORK.md`
- Commit: `Docs: Added demo video link`

**Challenges**:The full program run takes more than one minute, so the video was getting too long.

**Solution**: I started the run, explained the output while it was running, and then showed the final table.

**Time spent**:30 minuts

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: About 3.5 hours

**Most challenging part**:Feature 3, because I had to think about when a process starts and stops waiting.

**Most interesting learning**: `join()` makes the main thread wait, so only one process runs at a time, like a real single CPU.

**What I would do differently next time**:Save my program output from the start, so writing the answers is faster.

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

I learned that a thread is like a small worker that runs code inside the same program. In our code, the `Process` class implements `Runnable`, and `new Thread(process)` in `addProcessToQueue()` makes a thread for it. I learned that we must call `start()` and not `run()`, because `start()` creates a new thread and then calls `run()` inside it. I also learned that `join()` makes the main thread wait until the process thread finishes its time quantum, so only one process uses the "CPU" at a time. `Thread.sleep()` is used inside `run()` to simulate the process doing work for some milliseconds. One thing that surprised me is that a Java thread can be started only one time, so the code creates a new `Thread` every time a process goes back to the ready queue.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part was Feature 3, the waiting time tracking. It was hard because a process can wait in the ready queue many times, not only one time. At first I thought waiting time is only the time from creation until the first run, but that is wrong in Round-Robin. A process waits again every time it is re-queued after its time quantum. So I needed to know the exact moment the process enters the queue and the exact moment it starts running. I also had to decide where to put this code, because some of it is in the `Process` class and some is in the scheduler loop.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

First, I read the README again and drew the flow of one process on paper: enter queue, wait, run, re-queue. Then I saw that `addProcessToQueue()` is called every time a process enters the queue, so it was the best place to save the time with `markReady()`. I saw that `currentThread.start()` is the moment the process gets the CPU, so I called `startRunning()` just before it to add the waiting time. I tested after each small change by running the program and checking the numbers. For example, I checked that P1 has a small waiting time at first and bigger waiting time after it was re-queued. For the table, I fixed the column widths in `String.format` until the lines were aligned.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is used in many apps we use every day. In a web browser, one thread shows the page while another thread downloads data, so the page does not freeze. In a mobile photo app, each thread can make a thumbnail for a different image, like the example in our lecture. In a music player, one thread plays the music while the main thread handles the buttons. In a game, one thread can handle the graphics and another one handles the sound or the network. In our assignment, each process had its own thread, and the scheduler gave each one a time quantum, which is the same idea an OS uses to share the CPU between these apps.

### Optional: What would you like to learn more about?

I want to learn more about synchronization (locks and semaphores) and what happens when two threads change the same data.

### Optional: How confident do you feel about multithreading concepts now?

Intermediate. I understand `start()`, `join()` and `sleep()` well. I need more practice with threads that run at the same time and share data.

### Optional: Feedback on the assignment

The assignment was helpful because I could see Round-Robin working step by step in the output.

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

[Write your answer here.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[Write your answer here.]

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?]

2. **Runnable**: [When does P1 become Runnable?]

3. **Running**: [When is P1 Running?]

4. **Waiting**: [When and why would a thread be Waiting?]

5. **Terminated**: [When is P1 Terminated?]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[Describe the real-world scenario.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

### Example 2: [Name of application/scenario]

**Description**:
[Describe the real-world scenario or application.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

## Summary

**Key concepts I understood through these questions:**
1.
2.
3.

**Concepts I need to study more:**
1.
2.

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
