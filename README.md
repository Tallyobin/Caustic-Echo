CMPD353, Semester 1, 2022/2023

SECTION A: MULTIPLE CHOICE QUESTIONS (15 QUESTIONS, 30
MARKS)

Instruction: Please select the BEST answer from the given choices.

1. The following functions are all views in a computer system EXCEPT

A.

B
C.
D

batch system
computer hardware
application program

utilities

2. The following services fulfils convenience objective for operating system,
EXCEPT

A. error detection and response

B. program development

C, accounting

D. I/O devices

3. “The amount of time reserved for hardware setup for the purpose of running

programs.” The given explanation best explains

A. installing time

B. setup time

C.

schedule time

D. runtime

4. A process could be defined as the following, EXCEPT

 

A. unit of activity characterized by execution of a sequence of instruction

B. entity that can be assigned to and executed on a memory

C. instance of program running on a computer

D. program in execution

Page 2 of 11

CMPD353, Semester 1, 2022/2023

While a program is exccuting, it could be characterized by all the element as the
following, EXCEPT

A. thread

B. identifier

C. program counter

D. accounting information

Which of the following process state that is NOT relevant for 5-states process
model?

A. Exit.

B. Ready.

C. Running.

D. Blocked/suspend.

Select the relevant tables that are maintained by the operating system.
I- Memory Table

IT- I/O Table

IJJ- Deadlock Table

IV- State Table

A. I, II, WI and IV.
B. I, II and III.

C. I and II only.
D. III and IV only.

Page 3 of 11

10.

11,

12.

CMPD353, Semester I, 2022/2023

Atomic Operation could be defined as

 

A. fixation or action that ensures sequence of operation to be indivisible

B. section of code within process that request access to shared resources

C. requirement of ensuring no two concurrent processes are in critical section at
same time

D. events occur simultaneously

The following are all type of process interaction, EXCEPT
A. unaware of each other

B. indirectly unaware of each other

C. directly aware of each other
D.

indirectly aware of each other

Primary memory is also known as
A. secondary memory

B. virtual memory

C. real memory

D. hard disk memory

Whenever a new process is created, a series of actions are done by OS. The
following are the processes, EXCEPT

A. create or expand other data structures

B. assigns a unique process identifier

C. assigning a new process state

D. set up appropriate linkages

Among all of Disk Scheduling Algorithms, chooses tracks with the
minimum seek time, starting from the disk arm’s position.

A. SCAN

B. C-SCAN

C. SSTF

D. FIFO

Page 4 of 11

13.

14,

15.

CMPD353, Semester I, 2022/2023

Which of the following that is NOT the common type of buffering in traditional
OS?

A. Circular Buffer

B. Double Buffer

C. Internal Buffer

D. Single Buffer

“If a frame is locked, it may not be replaced by any incoming frames.”
The statement above refers to the occurrence of

A. frame locking

B. starvation

C. livelock

D. deadlock

The following set of operations are commonly doable in any OS, EXCEPT

. create
code

. delete

0A wD >

. write

Page 5 of 11

CMPD353, Semester 1, 2022/2023

SECTION B: SHORT ANSWERS QUESTIONS (5 QUESTIONS, 70 MARKS)

Instruction: Answer ALL questions. Wherever appropriate, show your work.

Question 1

X 1s a storage allocation scheme in which secondary memory can be addressed as

though it were part of main memory.

(a)

(b)

(Cc)

(d)

(€)

Define what is_X.
{1 mark]

Operating System (OS) brings into main memory a few pieces of program
simultaneously. State the term or specific name used to explain ‘the portion of

process that 1s in main memory’.

[1 mark]

Thrashing is a phenomena that could happen inside x Memory Allocation
Scheme. Explain your understanding on thrashing, and suggest how do OS cope

with this phenomena?
[4 marks]

Fetch Policy are consisting of demand paging and prepaging. What is the main

function of a fetch policy?

[1 mark]

Page Replacement Policy are consisting of policies that deals with selection of
pages In main memory to be replace when new pages are being brought in. One
of them is Optimal Policy. Given the following information, draw a table that
shows correct placement of pages accordingly.

Resident Set = 3 frames, Page address stream:-|2|3/2]1|5|/2|4|/5]3]2| 5]

{6 marks]

Page 6 of 11

CMPD353, Semester 1, 2022/2023

Question 2

_..._ There are THREE (3)_general aim of scheduling; low response time, high throughput _

and processor efficiency. Scheduling is also the bread and butter of multiprogramming.

(a) What is the specific type of scheduling that does not involve 5-state process

model?

{1 mark]

(b) Various scheduling policies employs different selection function and different
decision modes. As a result, throughput and the overhead of each scheduling

policies are different.

(i) What is selection function?
{1 mark]

(ii) | There are TWO (2) main categories of decision mode. Define and

explain both of the decision modes accordingly.
[5 marks]

(ii1) | Draw the scheduling diagram based on Highest Response Rate Ratio
Next (HRRN) scheduling policies. Calculate the waiting time for each
processes and derive the average waiting time as well. Use the following
information:-

Table 1
PROCESS | ARRIVAL | SERVICE

 

TIME TIME
A 0 3
B 2 16
Cc [4 4
an
g 2

(9 marks]
Page 7 of 11

CMPD353, Semester I, 2022/2023

Question 3

Concurrency 1s a property of a system in which several processes are executing —_

simultaneously, and potentially interacting with each other.

(a) Enforcement of single access is very important in order to ensure concurrency
in OS is ensured. Devise a situation that portrays single access enforcement and
briefly explain

[3 marks]

(b) Concurrent processes comes into conflict when they are competing for usage of
same type of resources.

(1) List down any TWO (2) examples of resources.
[2 marks]

(ii) As a result of competing processes, there are THREE (3) control
problems that must be managed by the operating system. List down and

briefly explain each of the control problems.
[6 marks]

Question 4

Memory management is very important. Despite getting cheaper and cheaper as the day

progresses, it is still quite slow compared to a Central Processing Unit (CPU)’s speed.

(a) Fill in accurate description for given terms. Draw the table in your answer

booklet.

Table 2

 

[2 marks]

Page 8 of 11

CMPD353, Semester 1, 2022/2023

(b) One of early method of memory management is employment of partitioning. It
have TWO (2) types, which are fixed partitioning and dynamic partitioning.

(1) State the TWO (2) subtypes of fixed partitioning.
[2 marks]

(11) —‘ In fixed partitioning, programs may not fit in the partition fully. Name

the problem that will happen as a result of employing fixed partitioning.

[1 mark]

(1) In dynamic partitioning, programs may not fit in the partition fully,
although allocated exact amount of memory needed. Name the problem
that will happen as a result of employing dynamic partitioning.

[1 mark]

(c) On a system using dynamic partitioning, assume that memory is allocated as

specified in Figure 1 before additional requests for 10k, 25k and 20k (in order)

are received.

Ktreos Hole bre Hole Berens | Hole ‘(great Hole KUpe wea Hole
, eke 7 15k | aL ORS or 40k 0h 45k oa 30k

 

<a 4 i ;
| Last placement | Last placement 4

Use the table below to show your answer. Draw this table in your answer booklet.

Figure 1

Determine which holes would be allocated to each of the memory request using the

following schemes:
Table 3

Partition Type Hole to Fit

First-fit

Next-fit

 

Page 9 of 1]

(d)

CMPD353, Semester 1, 2022/2023

 

    

Best-fit

[8 Marks]

Other than partitioning, another method commonly used for traditional memory
management system is buddy system.

(i) In your own word, explain about buddy system implementation.
[3 marks]

(it) | Given the following requirement and requests, draw an appropriate
representation of how will the system distribute memory allocation

using buddy system.

Size of memory: 500 kB
e Process A requested 110 kB of data to be executed
e Process B requested 85 kB of data to be executed
e Process C requested 200 kB of data to be executed
e Release Process B
e Release Process A

e Release Process C
[Smarks]

Page 10 of 11

CMPD353, Semester 1, 2022/2023

Question 5

For each proce sses, OS maintains specific page table that contains frame location for
each of the pages. The address is consisting of page number and offset within the page.
Create as many page tables as you could by referring from the paged memory shown

below.

 

 

 

[8 marks]

---End of Questions---

Page 11 of 11


































CMPD353, Semester 2, 2022/2023

SECTION A: MULTIPLE CHOICES (15 QUESTIONS, 30 MARKS)

Instruction: Please select the BEST answer from the given choices.

1. Select the related explanation for monitor in simple batch system.
A. Dhrect access to processor.
B. Considered as a system hardware.
C. Programs are not branched back to monitor once finished.
D

Jobs are being gathered and submitted to operator for processing.

2. The following are all elements in a process, EXCEPT
A. process ID
B. set of data
C. program code

D. execution context

3. The followings are all reasons for process creation, EXCEPT
A. new batch job
B. interactive logon
C. completing tasks

D. spawn by parent process

4. _____ is NOT one of the necessary control table for OS in a computer
environment.
A. Memory table
B. Explorer table
C. File table

D. I/O table

Page 2 of 11

CMPD353, Semester 2, 2022/2023

The concept of atomic operation is correctly explained by the following
Statements, EXCEPT

A. Section of code that requires access to shared resources.

B. Atomicity guarantees isolation from concurrent processes.

C. Atomic operation helps in implementation of mutual exclusion.

D. Sequence of instructions are ensured to execute as a group or none at all.

Refer to the image in Figure 1 shown below and select the INCORRECT

statement.

 

Figure 1 - Resource allocation graph

A. Deadlock happens.

B. P4 only requests for R2.

C. P2 requests both R3 and R4.

D. P3 ts holding R4 and requesting for R5.

Page 3 of 11

CMPD353, Semester 2, 2022/2023

Which of the following statement is correct with regards to dining philosophers

problem?

A.
B.
C,

D.

Involves six different philosophers.

All the philosophers may eat and think at the same time.

Philosophers are the metaphor for resources while the forks are the metaphor
for processes.

Forks are the metaphor for resources while the philosophers are the metaphor

for processes.

For scheduling policies, the selection function must be based on the following

criteria EXCEPT

A.

0 Aw >

priority

B. process size
C,
D

. execution characteristics of process

resource requirements

scheduling is the type of scheduling that executes most frequently.

. Medium term
. Short term

. Long term

l/O

. Hard disk drive is also known as
A.
B.
C.
D.

secondary memory
virtual memory
real memory

cache

Page 4 of 11

—- — CMPD353, Semester 2, 2022/2023

. “Aspect that measures size of information being transferred to and from devices.”

What is the most relevant aspect associated with above statement?
A. Size of the application

B. Complexity of usage

C. Data transfer rate

D. Unit of transfer

. Specify the device that has the fastest data transfer rate in term of byte (B).

A. Mice

B. Ethernet

C. Laser printer

D. Solid state drive (SSD)

. Refer to Figure 2 and select the most accurate statement.

Track track Sector

   
 
 

Disk Sector

.

a m\\

Lak y)

  

Figure 2 - Disk Parts

A. Actuator arm holds the platter.
B. Cluster is a combination of several track sector.
C. Track sector is combination of several track and platter.

D. Total amount of disk sector is more than total amount of track.

Page 5 of 11

CMPD353, Semester 2, 2022/2023

14, The followings are pure segmentation systems’ placement policy EXCEPT

15,

A. Best-fit
B. Next-fit
C. First-fit
D, Last-fit

The following statement correctly describe about files, EXCEPT
A. referenced by name

B. treated as a single entity

C. collection of related fields
D.

access control usually applied at file level

Page 6 of 11

CMPD353, Semester 2, 2022/2023

SECTION B: SHORT ANSWERS QUESTIONS (5 QUESTIONS, 70 MARKS)

Instruction: Answer ALL questions. Wherever appropriate, show your work.
Question 1

Deadlocks occur generally because processes deny each other’s resources, and none
can proceed to completion. It is a permanent occurrence that can’t be solved efficiently.
In general, there are several ways or strategies to deal with deadlock. One of the ways
to show a deadlock representation is by using resource allocation graphs.

Processes: PA, PB, PC, PD

Resources: R1 (3 units), R2 (2 units), R3 (2 units), R4 (3 units)

Requirements: Processes needs to have 3 different resources before it can be executed
/ completed.

Table 1 - Resource allocations

a :

PA
PD

  
   

   

 

   

(a) Draw a resource allocation Graph that represents information in Table 1.
[10 marks]

(b) Is there any deadlock occurrence based on resource allocation in Table 1?

Justify your answer.

[4 marks]

(c) There are four conditions in order for deadlock to happen. List down THREE

(3) out of the four conditions?
[3 marks]

Page 7 of 11

CMPD353, Semester 2, 2022/2023

Question 2

Security had always been a major and severe factor that interrupts execution of
processes and operating system’s task. There are two main categories of system access

threats: intruders and malicious software.

(a) List down TWO (2) examples of malicious software.

[2 marks]

(b) There are THREE (3) classes of intruders. Name and briefly describe each of

the classes.

[6 marks]

(c) Intrusion detection system (IDS) is security service that monitor and analyses
system to find unauthorized access or usage and provides real time warning to

the end user,

Name the TWO (2) type of IDS that are commonly used by end user.

[2 marks]

Question 3

Process is a combination of program code and a distinct set of associated data. There
are a lot unique and specific trait or elements that characterized data. X is a special

program that switches the processor from one process to another.

(a) Define what is X.
[1 mark]

(b) Name two main models that explains the states of processes. Name both models
accordingly.

[2 marks]

(c) Process termination stops and halts processes from executing properly. Provide

THREE (3) reasons that lead to the process termination.
[3 marks]

Page 8 of 11

(d)

 

CMPD353, Semester 2, 2022/2023

Figure 3 below shows the processes’ traces from three processes: X, Y and Z

 

Figure 3 - Process traces for X,Y and Z

Starting address of x program : 70.

Maximum number of instruction cycle : 3 cycles.

Draw the combined trace of ALL the processes.

[10 marks]

Question 4

(a)

(b)

Various input/output (I/O) devices are divided into THREE (3) main

categories.

(1) Name THREE (3) categories of I/O devices.
[3 marks]

(11) Specify any TWO (2) aspects or areas that differentiate thee I/O devices.
[2 marks]

There are several disk scheduling algorithms that could be used to ensure
performance of the disk I/O is optimized. Some of the common ones are FIFO,
SSTF and SCAN.

Head initial position: Track 75

Disc track request: 59, 73, 10, 170, 145, 30, 81, 120, 60, 24

Head movement: Decreasing.

Page 9 of 11]

CMPD353, Semester 2, 2022/2023

Use the graph in Figure 4 as your reference and draw the graph back on the

answer booklet.

0
Track
number
>
199
Time
Figure 4
(1) Based on given information, use the graph in Figure 4 to draw the

reading movement of the head on the disk, by using SCAN algorithm.
[9 marks]

(11) Calculate the average seek length.
[5 marks]

Question 5

Earlier computer machines utilize partitioning as early method of memory

management. Partitioning can be divided into two types, fixed partitioning, and Z

partitioning.

(a)

(b)

(c)

Define what is Z partitioning.
{1 mark]

Fixed partitioning is further divided into TWO (2) types. List down ALL of

them.
[2 marks]

Buddy system is another alternate strategy of memory management. It treats

available spaces as single block, and Splits into two equal buddies as required

Page 10 of 11

CMPD353, Semester 2, 2022/2023

by the processes. Based on the given condition in Figure 5 below, draw the

buddy system representation of memory allocation management.

Total amount of RAM 1000 KB/1 MB
First process to arrive, Process A — request for 122KB.
Second process arrive, Process B — request for 75KB.
Third process to arrive, Process C — request for 200KB.
Release process C.
Release process A.
Release process B.

Figure 5 - Buddy System

[5 marks]

---End of Questions---

Page 11 of 11
