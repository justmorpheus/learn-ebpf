# Function Arguments in eBPF

- Write an eBPF program that prints the command name passed to `execve` (using `argv`).
    - Objective: 
        - Attach an eBPF program to the `execve` syscall.
        - Extract and print the first argument (`argv[0]`), which is the name of the program being executed.

### Test:
- Run the script with different programs (e.g., `ls`, `cat`) and check if the output prints the correct program name.
