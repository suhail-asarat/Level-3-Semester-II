# Mahbub Sir's Part

**Reference Book:** [Abraham Silberschatz - Operating System Concepts [10th Edition] (2018)](https://drive.google.com/file/d/1KEqTC0N-nzLi87As5QUgHdNT_PDqrffN/view)

**Suggested Playlist:** [ Operating System by Neso Academy](https://www.youtube.com/playlist?list=PLBlnK6fEyqRiVhbXDGLXDk_OQAeuVcp2O)

*Note: Though Sir basically followed slides (mostly all of it) in class.*

## [Chapter 1 : Introduction](https://docs.google.com/presentation/d/1X2bvMNQYX-KxelpfE_mmQNt8PGtKxMJ7)

### Important Topics:
- I/O Subsystem $\star \star \star$

## [Chapter 2 : Operating-System Structures](https://docs.google.com/presentation/d/11W3CbERAoQ99Mm94uVIWoz71G2HcaeEv)

### Important Topics:
- User Goals and System Goals $\star \star \star$ [Viva]

## [Chapter 3 : Processes](https://docs.google.com/presentation/d/1ErJ_DNt0obRcFtBsBTH-bQe6LehgLmmT)


## [Chapter 4 : Threads and Concurrency](https://docs.google.com/presentation/d/1uSsqlOajplusGi_cRskKL-Y8LL-Qq60K)

### Important Topics:
- Resource Sharing $\star \star \star$
- Multicore and Multiprocessor Challenges $\star \star \star$

## [Chapter 5 : CPU Scheduling](https://docs.google.com/presentation/d/1QyjvYhQuniN886_as8YNJNQLdhmjtwuF)

### Important Topics:
- Sheculing Criteria (Definition) $\star$
- Round-Robin $\star \star \star$
- Priority Schedule $\star \star \star$


# Masud Sir's Part

**Reference Book:** [Abraham Silberschatz - Operating System Concepts [10th Edition] (2018)](https://drive.google.com/file/d/1KEqTC0N-nzLi87As5QUgHdNT_PDqrffN/view)

*Note: Sir followed both slides and book, specially during black-out days.*

## [Chapter 6 : Synchronization Tools](https://docs.google.com/presentation/d/12Dh3D3Dq0czLmPPhQKFnofPvrg_fOpy1)

- Concurrent Process

Definition: Cooperating Process

### 6.1 Background

- Producer-Consumer Code
  - Race Condition

### 6.2 Critical Section Problem

1. Mutual Exclusion
2. Progress
3. Bounded waiting

### 6.3 Peterson's Solution

Figure- 6.3, 6.4

### 6.4 Hardware Support for Synchronization

#### 6.4.1 Memory Barriers

#### 6.4.2 Hardware Instructions

Figure 6.5

- Atomic Process

Figure- 6.7, 6.8, 6.9

#### Mutex Locks
- Mutual Exclusion

Figure 6.10

Lock Contention

What is meant by "short duration"?

### 6.6 Semaphore

### 6.7 Monitors

#### 6.7.1 Monitor Usage

Abstract Data Type - ADT

Function-based Solution -> Monitor

Figure 6.11

#### 6.7.2 Implementing a Monitor using Semaphores

> How Monitors are used for reasoning?

#### 6.7.3 Reasuming Process within a Monitor

### 6.8 Liveness

#### 6.8.1 Deadlocks

#### 6.8.2 Priority


## [Chapter 7 : Synchronization Examples](https://docs.google.com/presentation/d/1GxKWaXd73FcMbsVDYY6dPOHe4at7oHQa)

Problems in Chapter 6
- Race Condition

Three Problems:
1. Bounded-Buffer
2. Readers-Writers
3. Dining Philoshophers

#### 7.1.1 The Bounded-Buffer Problem

- unshared data structure


Figure- 7.1, 7.2

#### 7.1.2 The Reader-Waiter Problem

- First Reader-Writer Problem
- Second Reader-Writer Problem

Figure- 7.3, 7.4 

#### 7.1.3 The Dining Philoshophers Probelm

Figure- 7.6, 7.7


## [Chapter 8 : Deadlocks](https://docs.google.com/presentation/d/1HRdmW3dpp5IY_VKrZlKD1DAKRrYIjJnv)

**Process:** A process is a program in execution.

**Thread:** A thread is a basic unit of CPU utilization.

### 8.1 System Model

### 8.2 Deadlock in Multitheaded Application

#### 8.2.1 Livelock

### 8.3 Deadlock Characterization

#### 8.3.1 Necessary Conditions

#### 8.3.2 Resource Allocation Graph $\star \star \star$

### 8.4 Methodsfor Handling Deadlocks

### 8.5 Deadlock Prevention

#### 8.5.1 Mutual Exclusion

#### 8.5.2 Hold and Wait

#### 8.5.3 No Preemption

#### 8.5.4 Circular Wait

### 8.6 Deadlock Avoidance

- Low Device Utilization
- Reduced System Throughput

#### 8.6.1 Safe State

#### 8.6.2 Resource Allocation Graph Algorithm

Figure- 8.9, 8.10

- Claim edge
- Assignment

#### 8.6.3 Banker's Algorithm

- Data Structure
  - Available
  - Max
  - Alloxation
  - Need

##### 8.6.3.1 Safety Algorithm

##### 8.6.3.2 

##### 8.6.3.3 An Illustrative Example

### 8.7 Deadlock Detection

#### 8.7.1 Single Instances of Each Resource Type

Figure 8.11

#### 8.7.3 Deletion-Algorithm Usage

## Self Reading

### 8.8 Recovery from Deadlock

#### 8.8.1 Process and Tread Termination

- Abort all deadlock processes

From Page-342, $\star \star \star$

Many factors may affect which process is chosen, including:

1. What the priority of the process is
2. How long the process has computed and how much longer the process will compute before completing its designated task
3. How many and what types of resources the process has used (for exam- ple, whether the resources are simple to preempt)
4. How many more resources the process needs in order to complete
5. How many processes will need to be terminated

#### 8.8.2 Resource Preemptioin

## [Chapter 9 : Main Memory](https://docs.google.com/presentation/d/1xy4uZLOnyJgqC1P9-VvnjlT3tRPdCVG4)

Figure 9.1

### 9.1 Address Binding

- Compile Time
- Execution TIme

#### 9.1.3 Logical Versus Physical Address Space

Figure 9.4

### 9.3 Paging

#### 9.3.1 Basic Method

Figure 9.8