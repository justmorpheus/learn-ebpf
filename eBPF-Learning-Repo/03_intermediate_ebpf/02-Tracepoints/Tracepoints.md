# Tracepoint Example


- Write a simple eBPF Python program that attaches to a raw tracepoint, prints "Hello World" every time a system call is made.
    - Objective: Attach an eBPF program to a raw tracepoint and print "Hello World" each time a system call occurs.


- Attach an eBPF program to the sched_switch tracepoint to log when context switches occur between processes
    - Objective: Attach an eBPF program to the sched_switch tracepoint and log the names of the processes involved in context switches.

### Test:
- Run the script and observe the logs to check if the process names are printed whenever a context switch happens.
    - Objective: Verify that the process names are logged when a context switch occurs.
