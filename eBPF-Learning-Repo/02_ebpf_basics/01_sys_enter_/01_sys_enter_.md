# Hello World eBPF Example

### Task:
Create an eBPF program that prints "Hello World!" whenever any syscall is made.

### Steps:
1. Use the `bpf_trace_printk()` function to print "Hello World!" when the `sys_enter` tracepoint is triggered.
2. Attach the eBPF program to the `sys_enter` tracepoint using `b.attach_raw_tracepoint()`.
3. Use `b.trace_print()` to view the kernel logs.

### Test:
Run the Python script and check the kernel trace buffer for the message "Hello World!"
