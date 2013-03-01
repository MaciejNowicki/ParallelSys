Parallel & Realtime Systems
===========================

Compile final.tex in the root the entire document.

Task B1
----------
### System Calls:

1.	Draw a figure of the organization of the sytem.  Relate the orgnizationof the
	System to the different types of operating systems discussed in the txt book 
	by tanenbaum.  What kind of operating system is it? Why?
2. 	Which portion executes in Kernel Mode? Which porions in user mode?  What is the
	differnce between user and kernel mode?
3. 	How is the kernel involved in the user level program?  Explain and elaborate!
4. 	How is control passed back to the user-level program?  Explain and elaborate!   

Task B2
----------
### System Calls:
1. 	Draw a sketch of the organisation of the system.   Relate this sketch to the one
	drew is task 1.
2. 	How is the system booted.  Outline and explain the boot process.
3. 	How are processes created from executable files?
4.  What information is found in executable files such as ELF files?  Why is this
	information necessary?
5.	A running process makes use of multiple memory regions.  What regions? Why are
	all the regions necessary?
6. 	How does a daemon process differ from processes studed in this task?

Task B3/A3
----------
### Scheduling:
1.	What is a scheduler?  What does it do and how does it work?
2.	Assume a thread can be in three different states:  running,blocked, ready.  Between
	the states there are various transitions.  Relate the states and transitions to the 
	code and actions in  the system.
3.	How does a thread queue data type work?
4. 	How does a timer queue work?
5.	How does preemption influence the design of an operating system?   How does it 
	influence the scheduler?
6.  How would the scheduler change if the system was to support processes with real-time
	requirements?
7.  **A3 Task**  discuss how the type of scheduling algorithm influence kernel data
	structures.  Also many advanced scheduling have a constant effective complexity
	O(1).  Howcan that be achieved?

Task B4/A4
----------
### Memory Management:
1.	In the system, memory can only be allocated in sizes of multiples (1,2,3,...) of four
	kiloytes.  What are the possible reasons for that?
2.	In your implementation, memory is maintained using a bitfield structureWhat would be
	the difference be if a linked list structure is used?
3.  **A4 Task** Draw  a figure of the page table that is used when the kernel boots.
4.	**A4 Task** Draw a figure of the memory map of the system.
5.	**A4 Task** The system only implements memory protection.  What would be needed to 
	implement:
	a. Paging?
	b. Virtual memory?
	c. Swapping?
	Outline the implementation for each case.  All 3 techniques can be combined.  
	Outline how this can be done.