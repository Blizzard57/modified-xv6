# Modified XV6

A modification of XV6 with scheduling algorithms, namely FCFS, Priority‐based and MLFQ, along with a couple of System Calls.

## Benchmark of Scheduling Algorithms

## Round Robin
Ticks taken to complete: 2340
This is fast

### FCFS
Ticks taken to complete: 2501

This just finds the process with minimum time and executes it. in my testing, this is the fastest algo

## PBS
Ticks taken to complete: 2747

In this the minimum priority process is found and sent to running, after that is finished, the algo checks again if there is any process with even less amount of priority and id there is, it executes that else continues with that as the least prioirty.

This is the second worst performer.

## MLFQ

Ticks taken to complete: 3012

The MLFQ algoritm gives up IO before its slice to retain the priority, thus making it the slowest.