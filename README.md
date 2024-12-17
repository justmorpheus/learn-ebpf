# Learn eBPF to Create Secret Detection Tool for Kubernetes Clusters

This repository is my journey to learn eBPF (Extended Berkeley Packet Filter) from the basics to more advanced use cases, with a focus on creating a secret detection tool for Kubernetes clusters. It includes examples of how to use eBPF for monitoring system calls, network events, file events, and more. The learning journey is broken down into different sections, each focused on specific concepts and tasks.


## Directory Structure

- **01_c_basics**: Basic C programming tasks to get you familiar with the C language, which is essential for writing eBPF programs.
  - `01_hello_world.md`: First steps in C programming.
  - `02_sum_function.md`: A simple function to sum numbers.
  - `03_pointer_basics.md`: Understanding pointers in C.

- **02_ebpf_hello_world**: Basic eBPF "Hello World" examples.
  - `01_syscall_execve.md`: Intercepting `execve` system calls using eBPF.
  - `02_filter_process.md`: Filtering processes with eBPF.

- **03_file_events**: Monitoring file-related system calls using eBPF.
  - `01_monitor_open.md`: Monitoring file `open` system calls.
  - `02_count_file_open.md`: Counting the number of times a file is opened.

- **04_network_events**: Monitoring network-related events using eBPF.
  - `01_monitor_tcp_connect.md`: Monitoring TCP connections.
  - `02_print_ip_addresses.md`: Printing source and destination IP addresses on network events.

- **05_maps_and_filters**: Working with eBPF maps and filters.
  - `01_event_counter.md`: Using BPF maps to count events.
  - `02_pid_filtering.md`: Filtering events based on process IDs.

- **06_kubernetes_setup**: Setting up a lightweight Kubernetes environment for eBPF testing.
  - `01_pod_setup.md`: Setting up a simple pod for eBPF experiments.
  - `02_test_ebpf_pod.md`: Testing eBPF in a pod environment.

## Prerequisites

- Basic knowledge of the C programming language.
- A Linux system with support for eBPF.
- Kubernetes (optional) for the Kubernetes-related examples.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/learn-ebpf.git
