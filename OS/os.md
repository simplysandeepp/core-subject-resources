Which of the following is NOT a function of OS?
A. Memory Management
B. Process Scheduling
C. Compilation of Programs
D. Device Management

👉 Answer: C
Reason: OS manages execution/resources, not program compilation.


Which OS structure gives maximum flexibility but poor performance?
A. Monolithic
B. Layered
C. Microkernel
D. Hybrid

👉 Answer: C
Reason: Services in user space → heavy IPC → slower.


A process is:
A. Program on disk
B. Program in execution
C. Binary file
D. Thread

👉 Answer: B
Reason: Process = active entity (running program).


PCB contains:
A. Process state
B. Program counter
C. CPU registers
D. All

👉 Answer: D
Reason: PCB stores complete execution context.


Invalid transition:
A. Ready → Running
B. Running → Waiting
C. Waiting → Ready
D. Waiting → Running

👉 Answer: D
Reason: Must go via Ready queue first.


Context switch happens when:
A. Interrupt
B. Process ends
C. Scheduler runs
D. All

👉 Answer: D
Reason: Any CPU switch between processes needs context save/restore.


Which causes starvation?
A. FCFS
B. Round Robin
C. Priority Scheduling
D. FIFO

👉 Answer: C
Reason: Low-priority processes may never execute.


If time quantum is very large in RR:
A. More context switches
B. Less response time
C. Acts like FCFS
D. No effect

👉 Answer: C
Reason: No preemption → behaves like FCFS.


Correct statement:
A. Threads have separate memory
B. Processes share memory
C. Threads are lightweight
D. Processes faster

👉 Answer: C
Reason: Threads share memory → low overhead.


User-level threads are managed by:
A. Kernel
B. Hardware
C. Thread library
D. OS scheduler

👉 Answer: C
Reason: Kernel unaware; handled in user space.


Which component is NOT directly involved in a context switch?

A. Program Counter
B. CPU Registers
C. Stack Pointer
D. Page Replacement Algorithm

👉 Answer: D
Reason: Context switch saves CPU state; page replacement is memory management, unrelated.


In a system with single CPU, maximum number of processes in Running state at a time?

A. 0
B. 1
C. 2
D. Depends on OS

👉 Answer: B
Reason: Single CPU executes only one process at a time.


Which of the following is stored in kernel space only?

A. User stack
B. Process Control Block
C. Application code
D. Heap memory

👉 Answer: B
Reason: PCB is managed by OS kernel for scheduling/control.


What is the primary purpose of a system call?

A. Run kernel faster
B. Allow user process to request OS services
C. Switch processes
D. Compile programs

👉 Answer: B
Reason: Interface between user space and kernel space.

Which mode transition happens during a system call?

A. User → User
B. Kernel → Kernel
C. User → Kernel
D. Kernel → User → Kernel

👉 Answer: C
Reason: System call transfers control to kernel mode.

Which of the following is NOT a process state?

A. New
B. Ready
C. Blocked
D. Compiled

👉 Answer: D
Reason: Compilation is not a runtime state.


A process moves to waiting state when:

A. It finishes execution
B. It is preempted
C. It waits for I/O
D. It enters ready queue

👉 Answer: C
Reason: Waiting = blocked for resource/I/O.

Which scheduling decision occurs most frequently?

A. Long-term scheduler
B. Medium-term scheduler
C. Short-term scheduler
D. I/O scheduler

👉 Answer: C
Reason: CPU scheduler runs very frequently (ms level).

Degree of multiprogramming is controlled by:

A. Short-term scheduler
B. Long-term scheduler
C. Medium-term scheduler
D. Dispatcher

👉 Answer: B
Reason: Long-term decides how many processes enter system.

Which of the following is true for dispatcher?

A. Selects next process
B. Performs context switch
C. Manages memory
D. Allocates I/O

👉 Answer: B
Reason: Dispatcher executes the switch decided by scheduler.


What is dispatch latency?

A. Time to execute process
B. Time to switch processes
C. Time to move process to ready queue
D. Time for I/O completion

👉 Answer: B
Reason: Delay between stopping one process and starting another.


Which of the following leads to process termination?

A. Normal completion
B. Fatal error
C. Killed by another process
D. All

👉 Answer: D
Reason: All are valid termination scenarios.


Which memory is shared among threads of same process?

A. Stack
B. Registers
C. Heap
D. Program Counter

👉 Answer: C
Reason: Threads share heap; stacks/registers are separate.

Which threading model allows many user threads to map to one kernel thread?

A. One-to-One
B. Many-to-One
C. Many-to-Many
D. Hybrid

👉 Answer: B
Reason: Multiple user threads handled by single kernel thread.


Main disadvantage of Many-to-One threading?

A. High overhead
B. No parallelism
C. Memory wastage
D. Slow I/O

👉 Answer: B
Reason: Only one thread executes → no multicore utilization.


Which is true about kernel-level threads?

A. Managed by user library
B. Faster to switch
C. OS schedules them
D. No system calls needed

👉 Answer: C
Reason: Kernel is aware → better scheduling but higher overhead.


What happens if a process executes fork()?

A. Process terminates
B. New child process created
C. Memory deleted
D. Context switch forced

👉 Answer: B
Reason: fork() duplicates process.


After fork(), child process has:

A. Same PID as parent
B. Different PID
C. No PID
D. Same memory reference

👉 Answer: B
Reason: Each process has unique PID.


Which is true about exec() system call?

A. Creates new process
B. Replaces process memory
C. Kills process
D. Changes PID

👉 Answer: B
Reason: Loads new program into existing process.


Which condition leads to zombie process?

A. Child finishes, parent not reading status
B. Parent finishes first
C. Process blocked
D. Deadlock

👉 Answer: A
Reason: Child terminated but not cleaned up by parent.

Which scheduling algorithm gives minimum average waiting time (theoretical)?
A. FCFS
B. SJF
C. Round Robin
D. Priority

👉 Answer: B
Reason: SJF is mathematically optimal (proof-based result).

Which algorithm suffers from convoy effect?
A. FCFS
B. SJF
C. RR
D. Priority

👉 Answer: A
Reason: One long job delays all short jobs.

Preemptive version of SJF is:
A. FCFS
B. Priority
C. SRTF
D. RR

👉 Answer: C
Reason: Shortest Remaining Time First = preemptive SJF.

Which scheduling ensures fairness (equal CPU share)?
A. FCFS
B. SJF
C. RR
D. Priority

👉 Answer: C
Reason: Time slicing ensures all processes get CPU.

Starvation can happen in:
A. FCFS
B. RR
C. SJF
D. Both SJF and Priority

👉 Answer: D
Reason: Long jobs or low priority may never execute.

Aging is used to:
A. Reduce turnaround time
B. Prevent starvation
C. Increase CPU utilization
D. Reduce context switch

👉 Answer: B
Reason: Gradually increases priority of waiting processes.

If time quantum is too small in RR:
A. Less context switch
B. High overhead
C. Acts like FCFS
D. No change

👉 Answer: B
Reason: Frequent switching → high overhead.

If time quantum is too large in RR:
A. More fairness
B. Acts like SJF
C. Acts like FCFS
D. Starvation

👉 Answer: C
Reason: No effective preemption.

Which metric is most important for interactive systems?
A. Throughput
B. Turnaround time
C. Response time
D. CPU utilization

👉 Answer: C
Reason: Fast first response matters most.

Turnaround time =
A. Completion - Arrival
B. Completion - Burst
C. Burst - Arrival
D. Waiting + Arrival

👉 Answer: A
Reason: Total time spent in system.

Waiting time =
A. Turnaround - Burst
B. Completion - Arrival
C. Burst - Turnaround
D. Arrival - Completion

👉 Answer: A
Reason: Time spent waiting in ready queue.

Which statement about SJF is correct?
A. Always implementable
B. Requires future knowledge
C. No starvation
D. Works only preemptively

👉 Answer: B
Reason: Needs burst time in advance → not practical.

Which metric is minimized by SJF?
A. Turnaround
B. Waiting
C. Response
D. Throughput

👉 Answer: B
Reason: Proven optimal for average waiting time.

In SRTF, preemption occurs when:
A. New process arrives
B. New process has smaller burst
C. Process finishes
D. Time quantum expires

👉 Answer: B
Reason: Only shorter remaining time causes preemption.

Which scheduling can lead to indefinite blocking?
A. FCFS
B. RR
C. SJF
D. Both SJF and Priority

👉 Answer: D
Reason: Long/low-priority jobs may never get CPU.

Which scheduling is non-preemptive priority?
A. CPU switches anytime
B. Runs till completion
C. Uses time quantum
D. Uses burst prediction

👉 Answer: B
Reason: No interruption once started.

If all processes arrive at same time, SJF becomes:
A. FCFS
B. Priority
C. RR
D. Undefined

👉 Answer: A
Reason: If burst same order, behaves like FCFS.

Which is true about RR?
A. No starvation
B. Zero waiting time
C. No context switching
D. Always optimal

👉 Answer: A
Reason: Every process eventually gets CPU.

Which factor increases context switch overhead?
A. Large burst time
B. Small time quantum
C. High priority
D. Less processes

👉 Answer: B
Reason: Frequent switching → overhead increases.

If CPU is idle and process arrives, scheduler:
A. Waits
B. Runs process immediately
C. Sends to waiting
D. Terminates

👉 Answer: B
Reason: No need to wait → direct execution.

Which scheduling uses time slicing + preemption?
A. FCFS
B. SJF
C. RR
D. Priority

👉 Answer: C
Reason: Core idea of Round Robin.

                                Process Synchronization –

What is the main goal of process synchronization?
A. Increase CPU speed
B. Avoid race conditions
C. Reduce memory usage
D. Improve I/O

👉 Answer: B
Reason: Synchronization ensures correct execution when processes share data.

Race condition occurs when:
A. Processes run slowly
B. Multiple processes access shared data concurrently
C. CPU is idle
D. Deadlock occurs

👉 Answer: B
Reason: Result depends on execution order → unpredictable output.

Critical section is:
A. Whole program
B. Part accessing shared resource
C. I/O operation
D. Memory allocation

👉 Answer: B
Reason: Code section where shared data is accessed.

Which condition is required for a correct solution to critical section problem?
A. Mutual exclusion
B. Progress
C. Bounded waiting
D. All

👉 Answer: D
Reason: All three are mandatory conditions.

Mutual exclusion means:
A. Only one process in system
B. Only one process in critical section
C. All processes run together
D. CPU idle

👉 Answer: B
Reason: Prevents simultaneous access to shared resource.

Busy waiting means:
A. Process sleeps
B. Process keeps checking condition continuously
C. Process terminates
D. CPU idle

👉 Answer: B
Reason: Wastes CPU cycles while waiting.

Which is a hardware solution for synchronization?
A. Semaphore
B. Monitor
C. Test-and-set
D. Mutex

👉 Answer: C
Reason: Atomic hardware instruction.

Semaphore is:
A. Variable
B. Integer with operations
C. Queue
D. Thread

👉 Answer: B
Reason: Integer accessed via wait() and signal().

Binary semaphore is also called:
A. Counting semaphore
B. Mutex
C. Monitor
D. Lock-free

👉 Answer: B
Reason: Only values 0/1 → mutual exclusion.

Wait operation does:
A. Increment semaphore
B. Decrement semaphore
C. Reset semaphore
D. Delete semaphore

👉 Answer: B
Reason: Decreases value; blocks if negative.

Signal operation does:
A. Increment semaphore
B. Decrement semaphore
C. Block process
D. Kill process

👉 Answer: A
Reason: Increases value; may wake waiting process.

Which condition is violated in race condition?
A. Progress
B. Mutual exclusion
C. Bounded waiting
D. Deadlock

👉 Answer: B
Reason: Multiple processes enter critical section simultaneously.

Which solution guarantees mutual exclusion but not bounded waiting?
A. Peterson’s
B. Test-and-set
C. Semaphore
D. Monitor

👉 Answer: B
Reason: Can cause starvation due to spinning.

Peterson’s solution works for:
A. Any number of processes
B. Only 2 processes
C. Only 1 process
D. Multicore only

👉 Answer: B
Reason: Designed specifically for 2 processes.

Main drawback of Peterson’s solution:
A. Deadlock
B. Busy waiting
C. Starvation
D. Memory leak

👉 Answer: B
Reason: Uses spin-waiting → wastes CPU.

Which is NOT a property of semaphore?
A. Atomic operations
B. Busy waiting always
C. Can block processes
D. Used for synchronization

👉 Answer: B
Reason: Can be implemented without busy waiting (blocking).

Counting semaphore is used when:
A. Only 1 resource
B. Multiple identical resources
C. No resources
D. Threads only

👉 Answer: B
Reason: Value represents number of available resources.

Which problem is solved using synchronization?
A. Deadlock
B. Race condition
C. Paging
D. Scheduling

👉 Answer: B
Reason: Synchronization ensures correct shared data access.

Which is a high-level synchronization construct?
A. Test-and-set
B. Semaphore
C. Monitor
D. Interrupt

👉 Answer: C
Reason: Monitor provides abstraction + safety.

Monitor ensures:
A. Multiple access
B. Automatic mutual exclusion
C. No synchronization
D. Deadlock

👉 Answer: B
Reason: Only one process enters monitor at a time.

Which scenario causes deadlock risk in semaphore?
A. Proper ordering
B. Incorrect ordering of wait()
C. Signal before wait
D. Single process

👉 Answer: B
Reason: Wrong order → circular waiting.

                    Deadlocks

Deadlock occurs when:
A. CPU is idle
B. Processes wait indefinitely for resources
C. Memory is full
D. Scheduling fails

👉 Answer: B
Reason: Circular waiting causes processes to block forever.

Which is NOT a necessary condition for deadlock?
A. Mutual exclusion
B. Hold and wait
C. Preemption
D. Circular wait

👉 Answer: C
Reason: “No preemption” is required, not preemption.

Mutual exclusion means:
A. Resource shared freely
B. Only one process uses resource at a time
C. CPU idle
D. Multiple processes execute

👉 Answer: B
Reason: Non-sharable resource.

Hold and wait means:
A. Process holds nothing
B. Process holds resources and waits for more
C. Process releases resources
D. CPU waits

👉 Answer: B
Reason: Key cause of deadlock.

No preemption means:
A. CPU cannot switch
B. Resource cannot be taken forcibly
C. Process stops
D. Scheduler inactive

👉 Answer: B
Reason: Resources released only voluntarily.

Circular wait means:
A. Processes in loop
B. Each process waits for another in cycle
C. CPU loop
D. Infinite loop

👉 Answer: B
Reason: P1→P2→P3→P1 dependency chain.

Deadlock prevention works by:
A. Ignoring deadlock
B. Breaking at least one necessary condition
C. Killing all processes
D. Increasing CPU

👉 Answer: B
Reason: If one condition is false → no deadlock.

Deadlock avoidance requires:
A. No information
B. Future knowledge of resource needs
C. Only current state
D. Random allocation

👉 Answer: B
Reason: Needs max resource demand (e.g., Banker’s).

Banker’s algorithm is used for:
A. Detection
B. Prevention
C. Avoidance
D. Recovery

👉 Answer: C
Reason: Allocates resources safely.

Safe state means:
A. No processes
B. System can avoid deadlock
C. No resources
D. CPU idle

👉 Answer: B
Reason: There exists a safe sequence.

Which condition is hardest to eliminate practically?
A. Mutual exclusion
B. Hold and wait
C. No preemption
D. Circular wait

👉 Answer: A
Reason: Many resources (like printers) cannot be shared.

Deadlock avoidance ensures:
A. No deadlock ever
B. Deadlock sometimes
C. System always in safe state
D. Faster execution

👉 Answer: C
Reason: Only safe allocations are allowed.

Which is true about safe vs unsafe state?
A. Unsafe = deadlock
B. Safe = deadlock
C. Unsafe may lead to deadlock
D. Same

👉 Answer: C
Reason: Unsafe ≠ deadlock, but risk exists.

Resource Allocation Graph (RAG) cycle means:
A. Always deadlock
B. Never deadlock
C. Deadlock only if single instance per resource
D. Deadlock only if multiple instances

👉 Answer: C
Reason: With single instance → cycle = deadlock.

Which technique allows deadlock but detects it later?
A. Prevention
B. Avoidance
C. Detection
D. Ignoring

👉 Answer: C
Reason: System checks and recovers later.

Which recovery method is used after detection?
A. Kill process
B. Resource preemption
C. Rollback
D. All

👉 Answer: D
Reason: All are valid recovery strategies.

Starvation vs Deadlock: starvation means:
A. All processes blocked
B. Some processes wait indefinitely
C. CPU idle
D. Deadlock always

👉 Answer: B
Reason: Only some processes affected.

Which approach is most commonly used in real OS?
A. Prevention
B. Avoidance
C. Detection
D. Ignore deadlock

👉 Answer: D
Reason: “Ostrich algorithm” → assume rare, ignore.

Banker’s algorithm fails when:
A. No processes
B. Resource requests exceed declared maximum
C. CPU idle
D. Single process

👉 Answer: B
Reason: Requires correct max demand info.

Which condition can be broken using resource ordering?
A. Mutual exclusion
B. Hold and wait
C. Circular wait
D. No preemption

👉 Answer: C
Reason: Ordering prevents cyclic dependency.
       
               Memory Management
What is the main goal of memory management?
A. Increase CPU speed
B. Efficient memory allocation
C. Reduce I/O
D. Increase processes

👉 Answer: B
Reason: OS allocates and manages memory efficiently among processes.

Logical address is generated by:
A. OS
B. CPU
C. Memory unit
D. Disk

👉 Answer: B
Reason: CPU generates logical (virtual) addresses.

Physical address is:
A. Address in disk
B. Address in RAM
C. Address in cache
D. Virtual address

👉 Answer: B
Reason: Actual location in main memory.

Address binding happens at:
A. Compile time
B. Load time
C. Execution time
D. All

👉 Answer: D
Reason: Can occur at any of these stages.

Which register holds base address of process?
A. Limit register
B. Base register
C. PC
D. MAR

👉 Answer: B
Reason: Base register stores starting physical address.

Limit register contains:
A. Start address
B. Process size
C. Page number
D. Frame number

👉 Answer: B
Reason: Defines bounds for protection.

What does MMU do?
A. Allocates CPU
B. Translates logical to physical address
C. Handles I/O
D. Scheduling

👉 Answer: B
Reason: Memory Management Unit performs address translation.

Paging is used to:
A. Remove external fragmentation
B. Remove internal fragmentation
C. Remove both
D. Increase CPU

👉 Answer: A
Reason: Paging eliminates external fragmentation.

Page size is:
A. Variable
B. Fixed
C. Random
D. Depends on process

👉 Answer: B
Reason: Paging uses fixed-size blocks.

Frame is:
A. Logical unit
B. Physical memory block
C. Disk block
D. Process

👉 Answer: B
Reason: Frame = fixed-size block in RAM.

Which fragmentation occurs in paging?
A. External
B. Internal
C. Both
D. None

👉 Answer: B
Reason: Last page may not fully utilize frame.

Segmentation suffers from:
A. Internal fragmentation
B. External fragmentation
C. No fragmentation
D. Paging fault

👉 Answer: B
Reason: Variable size segments → holes in memory.

Which technique uses both paging and segmentation?
A. Pure paging
B. Pure segmentation
C. Segmented paging
D. Swapping

👉 Answer: C
Reason: Combines advantages of both.

TLB is used to:
A. Increase page faults
B. Speed up address translation
C. Reduce memory size
D. Replace pages

👉 Answer: B
Reason: Cache for page table entries.

TLB hit means:
A. Page fault
B. Page found in TLB
C. Memory full
D. Process blocked

👉 Answer: B
Reason: Faster translation, no page table access needed.

Effective memory access time increases when:
A. TLB hit ratio high
B. Page fault occurs
C. Cache hit
D. CPU idle

👉 Answer: B
Reason: Page fault involves disk → very slow.

Page fault occurs when:
A. Page is in memory
B. Page not in memory
C. CPU busy
D. Memory full

👉 Answer: B
Reason: Required page must be fetched from disk.

Which page replacement is optimal?
A. FIFO
B. LRU
C. Optimal
D. Random

👉 Answer: C
Reason: Replaces page not needed for longest future time.

FIFO suffers from:
A. Thrashing
B. Belady’s anomaly
C. Deadlock
D. Starvation

👉 Answer: B
Reason: More frames can increase page faults.

LRU is based on:
A. Future knowledge
B. Past usage
C. Random choice
D. Priority

👉 Answer: B
Reason: Assumes recently used pages will be used again.

Thrashing occurs when:
A. CPU idle
B. Too many page faults
C. No processes
D. High memory

👉 Answer: B
Reason: System spends more time swapping than executing.

Which helps reduce thrashing?
A. Increase processes
B. Reduce processes
C. Increase page faults
D. Disable paging

👉 Answer: B
Reason: Lower load → fewer page faults.

Working set refers to:
A. All pages
B. Pages currently used by process
C. Free memory
D. Disk pages

👉 Answer: B
Reason: Set of actively used pages.

Which is true about virtual memory?
A. Uses only RAM
B. Uses disk as extension of RAM
C. No paging
D. No faults

👉 Answer: B
Reason: Allows execution beyond physical memory.

What is the main purpose of a file system?
A. Manage CPU
B. Store and organize data
C. Execute programs
D. Manage memory

👉 Answer: B
Reason: Provides structured storage and retrieval of data.

A file is:
A. Memory block
B. Collection of data
C. CPU instruction
D. Process

👉 Answer: B
Reason: Logical unit of storage.

Directory is used to:
A. Store processes
B. Organize files
C. Manage memory
D. Execute programs

👉 Answer: B
Reason: Helps in file organization and lookup.

Which file attribute is NOT common?
A. Name
B. Size
C. Color
D. Type

👉 Answer: C
Reason: Color is not a standard file attribute.

Which operation reads file content?
A. Open
B. Read
C. Write
D. Close

👉 Answer: B
Reason: Read operation retrieves data.

File pointer indicates:
A. File name
B. Current position in file
C. File size
D. Disk location

👉 Answer: B
Reason: Tracks current read/write position.

Which access method is fastest?
A. Sequential
B. Direct (random)
C. Indexed
D. Linked

👉 Answer: B
Reason: Direct access allows immediate jump.

Which structure stores file metadata?
A. Directory
B. Inode
C. Cache
D. Buffer

👉 Answer: B
Reason: Inode contains file info (size, pointers, etc.).

File system is stored on:
A. CPU
B. RAM
C. Secondary storage
D. Cache

👉 Answer: C
Reason: Persistent storage (disk/SSD).

Which system call creates a file?
A. open()
B. create()
C. read()
D. close()

👉 Answer: B
Reason: Explicit creation operation.

Which allocation method suffers from external fragmentation?
A. Contiguous
B. Linked
C. Indexed
D. All

👉 Answer: A
Reason: Needs continuous blocks → fragmentation occurs.

Which allocation method has slow access time?
A. Contiguous
B. Linked
C. Indexed
D. Direct

👉 Answer: B
Reason: Must follow pointers sequentially.

Which allocation supports direct access efficiently?
A. Linked
B. Indexed
C. Sequential
D. FIFO

👉 Answer: B
Reason: Index block allows direct lookup.

Main disadvantage of contiguous allocation:
A. Slow access
B. External fragmentation
C. Complex structure
D. No direct access

👉 Answer: B
Reason: Hard to find large continuous space.

In linked allocation, each block contains:
A. Data only
B. Pointer to next block
C. File size
D. Index

👉 Answer: B
Reason: Forms linked list of blocks.

Which allocation uses an index block?
A. Contiguous
B. Linked
C. Indexed
D. Sequential

👉 Answer: C
Reason: Stores addresses of all blocks.

Free space in disk is managed by:
A. Paging
B. Bitmap
C. Scheduling
D. CPU

👉 Answer: B
Reason: Bitmap tracks free/used blocks.

Which directory structure allows hierarchical organization?
A. Single-level
B. Two-level
C. Tree
D. Linear

👉 Answer: C
Reason: Tree structure supports folders/subfolders.

Which problem occurs in single-level directory?
A. Fast access
B. Name conflicts
C. Hierarchy
D. Security

👉 Answer: B
Reason: All files in one directory → duplicate names issue.

Which improves file access speed?
A. Disk scheduling
B. Caching
C. Paging
D. Context switching

👉 Answer: B
Reason: Frequently accessed data stored in faster memory.

Which is true about file sharing?
A. Always unsafe
B. Controlled via permissions
C. Not allowed
D. Only one user

👉 Answer: B
Reason: Access rights control usage.

Which is NOT a disk scheduling algorithm?
A. FCFS
B. SSTF
C. SCAN
D. SJF

👉 Answer: D
Reason: SJF is CPU scheduling, not disk.

