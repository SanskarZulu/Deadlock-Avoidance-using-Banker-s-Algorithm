# Deadlock-Avoidance-using-Banker-s-Algorithm
By Sanskar Sharma PRN: 0120180381

Deadlock Avoidance:
In deadlock avoidance, the request for any resource will be granted if the resulting state of the system doesn't cause deadlock in the system.
In order to avoid deadlocks, the process must tell OS, the maximum number of resources a process can request to complete its execution.

Deadlock has following characteristics.
1. Mutual Exclusion
2. Hold and Wait
3. No preemption
4. Circular wait

Banker's Algorithm:
Bankers’s Algorithm is resource allocation and deadlock avoidance algorithm which test all the request made by processes for resources, it checks for the safe state, 
if after granting request system remains in the safe state it allows the request and if there is no safe state it doesn’t allow the request made by the process.

