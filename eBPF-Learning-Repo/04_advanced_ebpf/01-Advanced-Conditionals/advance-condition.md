# Advanced Conditional Execution in eBPF

- Create an eBPF program that handles different syscalls with different actions based on the syscall opcode.
    - Objective:
        - Attach the eBPF program to the `sys_enter` tracepoint.
        - Implement `if`/`switch` conditions to handle different syscalls differently (e.g., print different messages for `execve`, `open`, etc.).
        - Use eBPF maps to store results and modify program flow based on conditions.

### Test:
- Run multiple programs and check the output to verify that the program prints different messages for different syscalls.
