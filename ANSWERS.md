# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:Process for a heavyweight and he has his own adress space     threds for lightweight work and it has Shared address space and it use shared memory  and i thenk we usedit Because  we need lightweight work  **

[Write your answer here. Consider: What is a process? What is a thread? How do they differ in terms of memory, resources, creation overhead? Why are threads more suitable for this simulation?]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:  If a process doesn’t finish within its time quantum it is preempted and moved to the end of the ready queu:**

[Write your answer here. Describe the specific behavior - where does the process go? When does it run again? Give an example from your actual program output showing a process that was re-queued.]

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what's happening in the output snippet you pasted]

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

[Write your answer here. For each state, explain when P1 enters that state during the simulation. Use your understanding of the code to trace through the lifecycle.]

1. **New**: [When is P1 in New state?]  thred is created but  not dtart

2. **Runnable**: [When does P1 become Runnable?]  after start thredis ready to run

3. **Running**: [When is P1 Running?]   in CPU

4. **Waiting**: [When/why would P1 be Waiting?]     its waiting for another thread to finesh

5. **Terminated**: [When is P1 Terminated?]    if its run and finsh

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: [Name of application/scenario]  Playstation 

**Description**: 
[Describe the real-world scenario or application]  Because it takes a lot of things like reading User input Or showing interface or Playing soundtracks

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]     Because it make sure to everything works smoothly and there is no threats starving

### Example 2: [Name of application/scenario]    Cinema application

**Description**: 
[Describe the real-world scenario or application]      There is a lot of user trying to book a seates at the same time

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]   its  preventing one user  from blocking others This ensures equal opportunity for all customers to complete their
bookings without delays  

---

## Summary

**Key concepts I understood through these questions:**
1.the difrent btwen threds and process 
2. round robin
3. Threads applications

**Concepts I need to study more:**
1. how can I apply threads in real life
2. How to use threads in the best way
