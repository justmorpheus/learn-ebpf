# Count with eBPF

- Task: Count File Access Events
    - Objective: 
        - Attach to the openat system call.
        - Use a BPF map to count how many times specific files (e.g., file.txt) are opened.
        - Print the file name and the access count.