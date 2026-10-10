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
| **Full Name** | Abdulwahab Zalah |
| **Student ID** | 445050007 |
| **University Email** | 445050007@std.psau.edu.sa |
| **GitHub Username** | Abdulwahab-zalah-0007 |
| **Repository Link** | https://github.com/Abdulwahab-zalah-0007/OS-Assignment1-abdulwahab-zalah |
 
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

### Entry 1 - October 9, 2026, 4:59 AM
**What I did**: I forked the starter repo and put my student ID.

**Details**:
- Forked `makopt/OS-Assignment1-Starter-481` and changed the name to `OS-Assignment1-abdulwahab-zalah`
- Checked that the repo is public
- Changed `studentID` in line 150 of `SchedulerSimulation.java` to my ID (445050007)
- Committed from GitHub website: `Set my student ID: 445050007`

**Challenges**: No big problems in this part.

**Solution**: Nothing needed.

**Time spent**: 15 minutes

---

### Entry 2 - October 9, 2026, 5:36 AM
**What I did**: I set up VS Code and ran the simulation the first time.

**Details**:
- Connected VS Code with my GitHub account and installed the Java extensions
- Set `git config` with my name and my university email
- Cloned my repo and ran `SchedulerSimulation.java` with the Run button
- First output showed 12 processes and time quantum 3000ms

**Challenges**: The command `java -version` was not recognized because I did not have JDK, and VS Code showed error "Java Language Server client: couldn't create connection to server" at 5:36 AM.

**Solution**: I installed JDK 21 (Eclipse Temurin) and restarted VS Code. After that the Java extension worked and the program ran.

**Time spent**: 1 hour

---

### Entry 3 - October 9, 2026, 7:23 AM
**What I did**: I did Feature 1, the process priority.

**Details**:
- Added `priority` field in the `Process` class
- Gave it random number from 1 to 10 in the constructor with `new Random().nextInt(10) + 1`
- Added `getPriority()` and printed the priority in `addProcessToQueue()`
- Checked that the queue is still FIFO
- Committed at 7:23 AM: `Feature 1: Added priority field to Process class`

**Challenges**: I got a lot of compile errors because the closing bracket `}` of the constructor was in the wrong place. Also I copied one `System.out.println` line two times by mistake.

**Solution**: I moved the `}` to after the priority line, deleted the extra line, and ran again to see the priority printed for all processes.

**Time spent**: 40 minutes

---

### Entry 4 - October 9, 2026, 8:06 PM
**What I did**: I did Feature 2, the context switch counter.

**Details**:
- Added `static int contextSwitches = 0;` in the `SchedulerSimulation` class
- Added `contextSwitches++` in the scheduler loop before `currentThread.start()`
- Printed `Total context switches` after the "ALL PROCESSES COMPLETED" message
- I counted the executions by hand from my output and got 24, same as the program
- Committed at 8:06 PM: `Feature 2: Implemented context switch counter`

**Challenges**: First I put the static variable inside `main` and got around 50 compile errors.

**Solution**: I moved it to the class level above `main`, because static variable can not be inside a method.

**Time spent**: 35 minutes

---

### Entry 5 - October 9, 2026, 9:15 PM
**What I did**: I did Feature 3, the waiting time tracking and the summary table.

**Details**:
- Added `creationTime` and `completionTime` to `Process` using `System.currentTimeMillis()`
- Added `markCompleted()`, `getTurnaroundTime()` and `getWaitingTime()`
- Saved the finished processes in a list `finishedProcesses` and called `markCompleted()` when process finish
- Printed a table with process name, burst time, waiting time and turnaround time
- Checked that turnaround = waiting + burst in every row (example P1: 24 + 1528 = 1552)
- Committed at 9:15 PM: `Feature 3: Added waiting time tracking and summary table`

**Challenges**: A process can finish in two places in the loop (after its quantum, or from `runToCompletion()`), so I was not sure where to save the completion time.

**Solution**: I added one check after both cases: if `process.isFinished()`, save the completion time and add it to the list.

**Time spent**: 1 hour

---

### Entry 6 - October 9, 2026, 10:46 PM
**What I did**: I started writing my documentation in `MY_WORK.md`.

**Details**:
- Filled the Student Information table (name, ID, university email, GitHub username, repo link)
- Committed at 10:41 PM: `Docs: Fill student information in MY_WORK.md`
- Fixed the space before the table and committed at 10:46 PM: `Docs: Fix table spacing`

**Challenges**: VS Code put `> -` automatically in an empty line and it can break the table. Also a file `image.png` appeared in my project folder by mistake.

**Solution**: I cleared the line until it is fully empty and deleted `image.png` so it is not committed.

**Time spent**: 30 minutes

---

## Development Log Summary

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

I learned that the Process class implements Runnable, so every process runs inside a new Thread(process).
In the time that the scheduler call start(), the thread start and Java calls the run() method.
Inside run(), I use Thread.sleep() to represent the time that the process uses the CPU.
The main thread calls join() to wait until the current quantum finish, and without it there is no order for process.
In my output, I saw P2 run for 3000ms, then back to the queue, and then run again for 402ms.
I also see P5 go back to the ready queue twice before it finish.
What surprised me is that a thread can not choose the time it starts, because the scheduler handle the order.


## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The hardest part for me was Feature 3, which is tracking the waiting time. It was difficult because a process can finish in two different places in the scheduler loop. At first, I did not know where to save the finish time because some processes might not appear in the table. I fixed this by checking if `process.isFinished()` in both cases and then calling `markCompleted()` and adding the process to the list. After that, I checked the numbers to make sure the turnaround time equals the waiting time plus the burst time. For example, P1 has 24 + 1528 = 1552. I learned that checking the results helps me find mistakes in my code.


## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I overcame the challenges by reading the error messages in VS Code carefully and checking the line number of each error.
For example, when I got around 50 errors in Feature 2, I understood that a static variable can not be inside the main method, so I moved it above main.
In Feature 1, I fixed the wrong place of the closing bracket `}` and deleted the line that I copied by mistake.
I also tested the program after each feature, before I committed it, so I could find the problem early.
To be sure about Feature 2, I counted the executions in my output by hand and I got 24, the same as the program.
I made a separate commit for each feature, so my work was organized and easy to follow.
This way of working, small steps and testing every time, helped me finish the assignment without big problems.


## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is used in many real applications that I use every day.
For example, a Brave web browser can load many pages and downloads at the same time using threads, so a slow page does not freeze the other tabs.
In a Spotify music player, one thread plays the audio and another thread handles the buttons, so the music does not stop when I press something.
Mobile games like Marvel Snap also use threads for drawing the screen, game logic, and the network at the same time.
In my assignment, each Process is like one of these tasks, and it runs inside its own Thread.
The time quantum of 3000ms is like the time slice that the system gives to each task, and the context switch happens when the scheduler changes to the next one.
This is similar to what my output showed, because every process got a turn and no process took the CPU for all the time.

### Optional: What would you like to learn more about?

nothing

### Optional: How confident do you feel about multithreading concepts now?


Confident. I understand threads, start(), join(), sleep() and Round-Robin. I need more practice with synchronization.


### Optional: Feedback on the assignment

The assignment was helpful and I learned a lot about threads and Git. My suggestion is to make the deadline more open, because not every student has the same free time, and the work needs a different number of hours for each student. More time can help students understand the code better, not only finish it fast.


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
