The preemptive priority scheduling algorithm is a popular operating system process management and job scheduling algorithm.

Every job that enters the job queue is assigned a priority based on which its execution takes place. As simple it sounds, the processes with a higher priority will be executed first and then the processes with the lower priorities will be executed.

If there are multiple processes in the queue with the same priority, then such jobs are executed in the order of their arrival often called as first come first served.

In this preemptive implementation of priority scheduling program in C, we consider the arrival time of the processes.

Since this is a preemptive job scheduling algorithm, the CPU can leave the process midway. The current state of the process will be saved by the context switch.

The system can then search for another process with a higher priority in the ready queue or waiting queue and start its execution.

Once the CPU comes back to the previous incomplete process, the job is resumed from where it was earlier paused.

Advantages
Preemptive priority scheduling is much more efficient as compared to the non-preemptive version.
This priority job scheduling algorithm is quite simple to implement.
The aging technique is implemented to reduce the starvation of lower priority processes.
The average turnaround time and waiting time is efficient.
Disadvantages
Indefinite blockage of the lower priority jobs.
For a system failure occurs, the unfinished lower priority jobs are removed from the system and cannot be recovered.
Note: This implementation of preemptive priority scheduling program in C with arrival time is compiled with GNU GCC compiler using Linux terminal on Linux Ubuntu operating system.
