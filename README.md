# Java implementation of RR and SJF scheduling algorithms

## RR Algorithm

Round Robin CPU Algorithm generally focuses on Time Sharing technique. 
The period of time for which a process or job is allowed to run in a pre-emptive method is called time quantum. 
Each process or job present in the ready queue is assigned the CPU for that time quantum, if the execution of the process is completed during that time then the process will end else the process will go back to the waiting table and wait for its next turn to complete the execution.

## SJF Algorith

Shortest Job first has the advantage of having a minimum average waiting time among all scheduling algorithms.
It is a Greedy Algorithm.
It may cause starvation if shorter processes keep coming. This problem can be solved using the concept of ageing.
It is practically infeasible as Operating System may not know burst times and therefore may not sort them. While it is not possible to predict execution time, several methods can be used to estimate the execution time for a job, such as a weighted average of previous execution times. 
SJF can be used in specialized environments where accurate estimates of running time are available.
