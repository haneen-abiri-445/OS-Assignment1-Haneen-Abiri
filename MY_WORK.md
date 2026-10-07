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
| **Full Name** | [Haneen Mohammed Abiri] |
| **Student ID** | [445052048] |
| **University Email** | 445052048@std.psau.edu.sa |
| **GitHub Username** | [haneen-abiri-445] |
| **Repository Link** | (https://github.com/haneen-abiri-445/OS-Assignment1-Haneen-Abiri.git) |
 
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

### Entry 1 - [October 6, 2026, 8:00 PM]
What I did: Set up the assignment repository and student information
Details:
- Opened the starter repository in VS Code.
- Configured my GitHub account and repository.
- Set my student ID in SchedulerSimulation.java.
- Ran the program to make sure the project was working.
- Created a commit for the student ID changes.
Challenges: I initially had some confusion with GitHub and the repository setup in VS Code.
Solution: I checked the Source Control panel and followed the Git workflow of staging, committing, and syncing the changes.
Time spent: 1 hour
---

### Entry 2 - [October 6, 2026, 10:00 PM]
What I did: Implemented Feature 1 and Feature 2
Details:
- Added the process priority field and related code for Feature 1.
- Tested the program after making the changes.
- Added the context switch counter for Feature 2.
- Ran the scheduler again and checked that the context switch count was displayed.
- Created separate commits for the features.
Challenges: Understanding where each feature needed to be added without changing the original scheduling behavior was challenging.
Solution: I worked on each feature separately, ran the program after the changes, and checked the output before moving to the next feature.
Time spent: 2 hours

---

### Entry 3 - [October 7, 2026, 6:00 PM]
What I did: Implemented and tested Feature 3
Details:
- Added creation time, waiting time, and last ready time to the Process class.
- Added methods to update and retrieve the waiting time.
- Added turnaround time calculation.
- Added a process statistics table showing burst time, waiting time, and turnaround time.
- Fixed duplicate process entries and a syntax error during testing.
- Committed the completed Feature 3 changes.
Challenges: The first version of the statistics table displayed duplicate processes, and I also had a missing brace that caused a compilation error.
Solution: I traced the problem through the processMap and changed the summary to use a completed-process list. I also checked the braces around the scheduler loop and fixed the syntax error.
Time spent: 2 hours

---

### Entry 4 - [October 7, 2026, 7:30 PM]
What I did: Tested the completed features and reviewed the program output
Details:
- Ran the scheduler after completing the three features.
- Checked that priorities were displayed when processes entered the ready queue.
- Checked the total context switch count.
- Reviewed the waiting time and turnaround time table.
- Verified that the program completed without compilation errors.
Challenges: Some errors appeared while integrating the waiting time feature.
Solution: I checked the affected code section, fixed the syntax and process-tracking issues, and ran the program again.
Time spent: 1 hour

---

### Entry 5 - [October 7, 2026, 8:30 PM]
What I did: Reviewed the assignment requirements and prepared the documentation
Details:
- Reviewed the required features and commit history.
- Checked that each feature had its own commit.
- Opened MY_WORK.md and started completing the required documentation.
- Reviewed the final program output and the required submission checklist.
Challenges: Making sure that all required parts of the assignment were completed and documented correctly.
Solution: I followed the assignment checklist and checked each requirement before moving to the next part.
Time spent: 1 hour
### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [7 hours]

**Most challenging part**:The most challenging part was implementing the waiting time tracking feature and making sure the final statistics were correct. I also had to fix duplicate processes in the final table and a syntax error during testing.

**Most interesting learning**:The most interesting part was seeing how Round-Robin scheduling works in practice. I learned how the time quantum causes processes to return to the ready queue and how context switches happen between processes.

**What I would do differently next time**:Next time, I would plan the implementation of each feature before changing the code. I would also test smaller parts of the program more frequently to find errors earlier.

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

[I learned that multithreading allows different processes to be executed using threads. In my program, the Process class implements Runnable, and a new thread is created using new Thread(process). The Thread.start() method starts the process, while Thread.sleep() is used to simulate the process running for its time quantum. I also learned that Thread.join() makes the scheduler wait for the current thread to finish before continuing. The ready queue controls the order in which processes are selected. This helped me understand how threads and the scheduler work together in a Round-Robin system.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**The most challenging part was implementing the waiting time tracking feature. I had to understand when a process enters the ready queue and when it starts running. During testing, the statistics table also displayed some processes more than once. This happened because the same process could be added to the queue again after its time quantum ended. I fixed this by keeping track of completed processes separately for the final table. I also fixed a syntax error caused by a missing brace while testing the scheduler.** *(5-7 sentences)*

[Write your answer here.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by working on each feature separately and testing the program after every change. When I found duplicate processes in the final table, I checked how processes were stored and re-added to the ready queue. I then used a separate list to keep track of completed processes. When a compilation error appeared, I checked the surrounding code and fixed the missing brace. I also compared the program output with the expected behavior of the scheduler. Testing after each change helped me find and solve problems before moving to the next feature.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading and scheduling are used in many real-world systems where multiple tasks need to share CPU time. Operating systems use scheduling techniques to manage processes and give each process a chance to run. Round-Robin scheduling is useful for interactive systems because it gives each process a fixed time quantum. Context switching allows the system to move from one process to another when the time quantum ends. A similar idea can be used in servers to handle multiple requests fairly. This assignment helped me understand how these concepts work in a practical program.]

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

[A process is an independent program or task, while a thread is a smaller unit of execution within a process. In my project, the Process class represents a simulated process, but the actual execution is handled by a Java Thread. In addProcessToQueue(), the code uses new Thread(process) to create a thread for the process. Processes generally have their own memory space, while threads within the same process can share resources. This project helped me understand the difference between the simulated process and the Java thread that executes it.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[The ready queue follows Round-Robin scheduling because each process receives a fixed time quantum of 4000ms. For example, P1 started with a burst time of 9313ms and after its first quantum, it had 5313ms remaining, so it was added back to the ready queue. After its second quantum, it had 1313ms remaining and was added back to the queue again. P1 was therefore re-queued twice before it finished its execution. This shows how Round-Robin gives each process a fair turn before returning to a process that still has remaining time.]

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

1. **New**: [P1 is in the New state when new Thread(process) is created inside addProcessToQueue().]

2. **Runnable**: [When does P1 become Runnable? P1 becomes Runnable when Thread.start() is called by the scheduler.]

3. **Running**: [When is P1 Running? P1 is Running when its run() method starts executing and it begins its time quantum.]

4. **Waiting**: [When and why would a thread be Waiting? P1's thread sleeps during Thread.sleep() while simulating its time quantum. The main thread also waits when it calls Thread.join().]

5. **Terminated**: [When is P1 Terminated? P1 is Terminated when its run() method finishes and the thread completes its execution. ]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[An operating system uses Round-Robin scheduling to share CPU time among multiple running programs. Each running program can be treated like a process in my simulation, and the time quantum determines how long it can use the CPU before another process gets a turn. A context switch happens when the CPU moves from one process to another.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability? Round-Robin provides fairness because every process gets a turn. It also improves responsiveness because one process cannot keep the CPU for too long. The fixed time quantum makes the scheduling behavior predictable.]

### Example 2: [Name of application/scenario]

**Description**:
[Describe the real-world scenario or application. A web server can use threads to handle multiple client requests at the same time. Each request can be treated like a process in my simulation, while the time quantum represents the amount of CPU time given to each request. A context switch occurs when the server switches between threads handling different requests.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability? Round-Robin can provide fair CPU access when many requests are competing for resources. It helps prevent one request from using the CPU for too long and improves responsiveness for other requests.]

## Summary

**Key concepts I understood through these questions:**
1- How Round-Robin scheduling uses a fixed time quantum.
2- How context switching allows the CPU to move between processes.
3- How Java threads are created and managed during process execution.

**Concepts I need to study more:**
1. Different thread lifecycle states and transitions.
2. How real operating systems implement CPU scheduling.

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
