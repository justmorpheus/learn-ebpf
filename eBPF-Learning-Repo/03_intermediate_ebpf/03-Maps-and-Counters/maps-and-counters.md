# eBPF Maps and Counters

### Task:
Create a counter using an eBPF map that tracks how many times a specific syscall is called (e.g., `open` syscall).

### Steps:
1. Use `BPF_HASH` to create a map that stores the count of the `open` syscall.
2. Attach the program to the `sys_enter` tracepoint and update the map whenever the `open` syscall occurs.
3. Print the count of `open` syscalls.

### Test:
Run the program and check the kernel logs to see the count of `open` syscalls.
