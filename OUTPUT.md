/*
Output: (three outputs attached)
 
Example 1: Deadlock avoidance safety sequence found!


                                    OS Lab Assignment
                                Submitted by: Sanskar Sharma
                                     PRN: 0120180381

                        Deadlock Avoidance using Banker's Algorithm
                Enter the number of processes: 5

                Enter the name of each process:
                    Enter the name of 1 process: P0

                    Enter the name of 2 process: P1

                    Enter the name of 3 process: P2

                    Enter the name of 4 process: P3

                    Enter the name of 5 process: P4

                Enter the number of resources: 4

                Enter the name of each resource:
                    Enter the name of 1 resource: A

                    Enter the name of 2 resource: B

                    Enter the name of 3 resource: C

                    Enter the name of 4 resource: D

                Enter the allocation matrix:
                  Enter the allocated instances for process P0 of resource A : 0

                  Enter the allocated instances for process P0 of resource B : 0

                  Enter the allocated instances for process P0 of resource C : 1

                  Enter the allocated instances for process P0 of resource D : 2

                  Enter the allocated instances for process P1 of resource A : 1

                  Enter the allocated instances for process P1 of resource B : 0

                  Enter the allocated instances for process P1 of resource C : 0

                  Enter the allocated instances for process P1 of resource D : 0

                  Enter the allocated instances for process P2 of resource A : -3

                  Re-enter (instances cannot be negative): 1

                  Enter the allocated instances for process P2 of resource B : 3

                  Enter the allocated instances for process P2 of resource C : 5

                  Enter the allocated instances for process P2 of resource D : 4

                  Enter the allocated instances for process P3 of resource A : 0

                  Enter the allocated instances for process P3 of resource B : 6

                  Enter the allocated instances for process P3 of resource C : 3

                  Enter the allocated instances for process P3 of resource D : 2

                  Enter the allocated instances for process P4 of resource A : 0

                  Enter the allocated instances for process P4 of resource B : 0

                  Enter the allocated instances for process P4 of resource C : 1

                  Enter the allocated instances for process P4 of resource D : 4

                Enter the max matrix:
                  Enter the max instances for process P0 of resource A : 0

                  Enter the max instances for process P0 of resource B : 0

                  Enter the max instances for process P0 of resource C : 1

                  Enter the max instances for process P0 of resource D : 2

                  Enter the max instances for process P1 of resource A : 1

                  Enter the max instances for process P1 of resource B : 7

                  Enter the max instances for process P1 of resource C : 5

                  Enter the max instances for process P1 of resource D : 0

                  Enter the max instances for process P2 of resource A : 2

                  Enter the max instances for process P2 of resource B : 3

                  Enter the max instances for process P2 of resource C : 5

                  Enter the max instances for process P2 of resource D : 6

                  Enter the max instances for process P3 of resource A : -4

                  Re-enter (instances cannot be negative): 0

                  Enter the max instances for process P3 of resource B : 6

                  Enter the max instances for process P3 of resource C : 5

                  Enter the max instances for process P3 of resource D : 2

                  Enter the max instances for process P4 of resource A : 0

                  Enter the max instances for process P4 of resource B : 6

                  Enter the max instances for process P4 of resource C : 5

                  Enter the max instances for process P4 of resource D : 3

                  Re-enter (max instances of a resource for a process should be greater than or equal to allocated): 6

                Enter the available instances for each resource:
                  Available intances of the resource A : 1

                  Available intances of the resource B : 5

                  Available intances of the resource C : 2

                  Available intances of the resource D : 0

                        Tabular Representation of problem.
                    Allocation      Max         Need

                    A  B  C  D   A  B  C  D   A  B  C  D

                P0  0  0  1  2   0  0  1  2   0  0  0  0
                P1  1  0  0  0   1  7  5  0   0  7  5  0
                P2  1  3  5  4   2  3  5  6   1  0  0  2
                P3  0  6  3  2   0  6  5  2   0  0  2  0
                P4  0  0  1  4   0  6  5  6   0  6  4  2

                All process have successfully executed!!
                Deadlock has been successfully avoided!
                        The Safety Sequence is:
                    P0 --> P2 --> P3 --> P4 --> P1
--------------------------------
Process exited after 137.9 seconds with return value 0
Press any key to continue . . .

Example 2: Deadlock avoidance safety sequence found!



                                    OS Lab Assignment
                                Submitted by: Sanskar Sharma
                                     PRN: 0120180381

                        Deadlock Avoidance using Banker's Algorithm
                Enter the number of processes: 5

                Enter the name of each process:
                    Enter the name of 1 process: P0

                    Enter the name of 2 process: P1

                    Enter the name of 3 process: P2

                    Enter the name of 4 process: P3

                    Enter the name of 5 process: P4

                Enter the number of resources: 3

                Enter the name of each resource:
                    Enter the name of 1 resource: A

                    Enter the name of 2 resource: B

                    Enter the name of 3 resource: C

                Enter the allocation matrix:
                  Enter the allocated instances for process P0 of resource A : 0

                  Enter the allocated instances for process P0 of resource B : 1

                  Enter the allocated instances for process P0 of resource C : 0

                  Enter the allocated instances for process P1 of resource A : 2

                  Enter the allocated instances for process P1 of resource B : 0

                  Enter the allocated instances for process P1 of resource C : 0

                  Enter the allocated instances for process P2 of resource A : 3

                  Enter the allocated instances for process P2 of resource B : 0

                  Enter the allocated instances for process P2 of resource C : 2

                  Enter the allocated instances for process P3 of resource A : 2

                  Enter the allocated instances for process P3 of resource B : 1

                  Enter the allocated instances for process P3 of resource C : 1

                  Enter the allocated instances for process P4 of resource A : 0

                  Enter the allocated instances for process P4 of resource B : 0

                  Enter the allocated instances for process P4 of resource C : 2

                Enter the max matrix:
                  Enter the max instances for process P0 of resource A : 7

                  Enter the max instances for process P0 of resource B : 5

                  Enter the max instances for process P0 of resource C : 3

                  Enter the max instances for process P1 of resource A : 3

                  Enter the max instances for process P1 of resource B : 2

                  Enter the max instances for process P1 of resource C : 2

                  Enter the max instances for process P2 of resource A : 9

                  Enter the max instances for process P2 of resource B : 0

                  Enter the max instances for process P2 of resource C : 2

                  Enter the max instances for process P3 of resource A : 2

                  Enter the max instances for process P3 of resource B : 2

                  Enter the max instances for process P3 of resource C : 2

                  Enter the max instances for process P4 of resource A : 4

                  Enter the max instances for process P4 of resource B : 3

                  Enter the max instances for process P4 of resource C : 3

                Enter the available instances for each resource:
                  Available intances of the resource A : 3

                  Available intances of the resource B : 3

                  Available intances of the resource C : 2

                        Tabular Representation of problem.
                    Allocation      Max         Need

                    A  B  C   A  B  C   A  B  C

                P0  0  1  0   7  5  3   7  4  3
                P1  2  0  0   3  2  2   1  2  2
                P2  3  0  2   9  0  2   6  0  0
                P3  2  1  1   2  2  2   0  1  1
                P4  0  0  2   4  3  3   4  3  1

                All process have successfully executed!!
                Deadlock has been successfully avoided!
                        The Safety Sequence is:
                    P1 --> P3 --> P4 --> P0 --> P2
--------------------------------
Process exited after 61.87 seconds with return value 0
Press any key to continue . . .

Example 3: Unsafe states/ no safety sequence.


                                    OS Lab Assignment
                                Submitted by: Sanskar Sharma
                                     PRN: 0120180381

                        Deadlock Avoidance using Banker's Algorithm
                Enter the number of processes: 5

                Enter the name of each process:
                    Enter the name of 1 process: P1

                    Enter the name of 2 process: P2

                    Enter the name of 3 process: P3

                    Enter the name of 4 process: P4

                    Enter the name of 5 process: P5

                Enter the number of resources: 3

                Enter the name of each resource:
                    Enter the name of 1 resource: A

                    Enter the name of 2 resource: B

                    Enter the name of 3 resource: C

                Enter the allocation matrix:
                  Enter the allocated instances for process P1 of resource A : 0

                  Enter the allocated instances for process P1 of resource B : 1

                  Enter the allocated instances for process P1 of resource C : 0

                  Enter the allocated instances for process P2 of resource A : 2

                  Enter the allocated instances for process P2 of resource B : 0

                  Enter the allocated instances for process P2 of resource C : 0

                  Enter the allocated instances for process P3 of resource A : 3

                  Enter the allocated instances for process P3 of resource B : 0

                  Enter the allocated instances for process P3 of resource C : 3

                  Enter the allocated instances for process P4 of resource A : 2

                  Enter the allocated instances for process P4 of resource B : 1

                  Enter the allocated instances for process P4 of resource C : 1

                  Enter the allocated instances for process P5 of resource A : 0

                  Enter the allocated instances for process P5 of resource B : 0

                  Enter the allocated instances for process P5 of resource C : 2

                Enter the max matrix:
                  Enter the max instances for process P1 of resource A : 0

                  Enter the max instances for process P1 of resource B : 0

                  Re-enter (max instances of a resource for a process should be greater than or equal to allocated): 0

                  Re-enter (max instances of a resource for a process should be greater than or equal to allocated): 5

                  Enter the max instances for process P1 of resource C : 3

                  Enter the max instances for process P2 of resource A : 3

                  Enter the max instances for process P2 of resource B : 2

                  Enter the max instances for process P2 of resource C : 2

                  Enter the max instances for process P3 of resource A : 9

                  Enter the max instances for process P3 of resource B : 0

                  Enter the max instances for process P3 of resource C : 2

                  Re-enter (max instances of a resource for a process should be greater than or equal to allocated): 2

                  Re-enter (max instances of a resource for a process should be greater than or equal to allocated): 2

                  Re-enter (max instances of a resource for a process should be greater than or equal to allocated): 2

                  Re-enter (max instances of a resource for a process should be greater than or equal to allocated): 5

                  Enter the max instances for process P4 of resource A : 5

                  Enter the max instances for process P4 of resource B : 5

                  Enter the max instances for process P4 of resource C : 4

                  Enter the max instances for process P5 of resource A : 3

                  Enter the max instances for process P5 of resource B : 3

                  Enter the max instances for process P5 of resource C : 9

                Enter the available instances for each resource:
                  Available intances of the resource A : 1

                  Available intances of the resource B : 1

                  Available intances of the resource C : 1

                        Tabular Representation of problem.
                    Allocation      Max         Need

                    A  B  C   A  B  C   A  B  C

                P1  0  1  0   0  5  3   0  4  3
                P2  2  0  0   3  2  2   1  2  2
                P3  3  0  3   9  0  5   6  0  2
                P4  2  1  1   5  5  4   3  4  3
                P5  0  0  2   3  3  9   3  3  7
                        No safety Sequence can avoid deadlock!!
--------------------------------
Process exited after 96.96 seconds with return value 0
Press any key to continue . . .
*/
