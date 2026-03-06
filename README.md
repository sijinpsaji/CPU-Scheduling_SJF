Shortest Job First (SJF) is a scheduling policy that selects the waiting process with the smallest execution time (Burst Time) to execute next. This specific implementation is non-preemptive, meaning once a process is allocated to the CPU, it holds the CPU until it terminates or completes its burst time.
Key Characteristics:

    Greedy Approach: It always picks the "shortest" task available at the current time.

    Minimized Waiting Time: It is optimal because it reduces the average waiting time for a given set of processes.

    Starvation: While efficient, it can lead to "starvation" for longer processes if shorter processes keep arriving.
