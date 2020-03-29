# 1st-revision
about round robin
Round Robin is a CPU scheduling algorithm where each process is assigned a fixed time slot in a cyclic way.
It is simple, easy to implement, and starvation-free as all processes get fair share of CPU.
It is preemptive as processes are assigned CPU only for a fixed slice of time at most.
The disadvantage of it is more overhead of context switching.
ompletion Time: Time at which process completes its execution.
Turn Around Time: Time Difference between completion time and arrival time. Turn Around Time = Completion Time – Arrival Time
Waiting Time(W.T): Time Difference between turn around time and burst time.
Waiting Time = Turn Around Time – Burst Time.
example : using round-robin algorithm having same arrival time with time quantum 1 unit and to find average waiting and turn around time.
Processes  Arrival time  Burst time 
 1            0             3
 2            0             4
 3            0             3
