# Shortest Job First and Round Robin
## SJF
The shortest job first (SJF) or shortest job next, is a scheduling policy that selects the waiting process with the smallest execution time to execute next.
Algorithm: 
Sort all the processes according to the arrival time. 
Then select that process that has minimum arrival time and minimum Burst time. 
After completion of the process make a pool of processes that arrives afterward till the completion of the previous process and select that process among the pool which is having minimum Burst time. 
the implementation of it is https://github.com/menna27ahmed/sfjj/blob/main/src/sfj/Sfj.java
the output is 
![My Image](https://github.com/menna27ahmed/sfjj/blob/main/sfj%20output.png)

## RR
The name of this algorithm comes from the round-robin principle, where each person gets an equal share of something in turns. It is the oldest, simplest scheduling algorithm, which is mostly used for multitasking.
In Round-robin scheduling, each ready task runs turn by turn only in a cyclic queue for a limited time slice. This algorithm also offers starvation free execution of processes.
the implementation of it is https://github.com/menna27ahmed/sfjj/blob/main/src/sfj/rr.java
the output is 
![My Image](https://github.com/menna27ahmed/sfjj/blob/main/rr%20output.png)
