# Simple Conditionals with eBPF

- Create an eBPF program that tracks how many times `execve` and `open` syscalls are made. If `execve` count is more than 5, print "Many programs executed!"
    - Objective:
        - Track the count of `execve` and `open` syscalls using a map.
        - Add conditionals to print different messages based on the count.

### Test:
- Run a program multiple times (e.g., `ls`, `cat`).
    - Check the output to see if the program prints "Many programs executed!" when more than 5 `execve` syscalls are made.
