# RTOS Tutorial

## Real-Time System
### Hard Real-Time (HRT)
  * Must meet the dealine
### Soft Real-Time (SRT)
  * Some deadline can be violated in

## Tech Term
### Task
  * A processor executes a task and it is the unit for computation
### Job
  * An instance of a task is called a job   
### Hyperperiod
  * The Least Common Multiple (LCM) of the periods of all periodic task 
### Preemptive/Non-preemptive
  * Task can be interrupted by higher-priority tasks or not 
### Content Switch
  * Another task gains control of the CPU from current task
### Phase 
  * initial shift or delay applied to the first job for the alignment
### Jitter
  * Maximal span of uncertainty in release time [r-, r+]

## CPU Register
### Status Register
* Store information about the state of the processor
### Program Counter
* Track of the memory address of the next instruction to be executed
### Stack Pointer
* Keeps track of the top of the stack in computer memory
### General Purpose Register
* A storage location within a CPU that can store data temporarily for arithmetic, logical, or data movement operations

## Task State
* Ready
* Running
* Blocked
* Suspend
 
## Task Categories
### Periodic Task
T(Period, Exec Time, Deadline)
### Aperiodic Task
### Sporadic Task

## Scheduler Categories
### Static Scheduler

## Sy
