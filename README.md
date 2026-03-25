# proc-netscan
A lightweight utility that interfaces directly with the Linux `/proc` virtual filesystem. By parsing kernel network tables and cross-referencing process file descriptors, it provides a real-time mapping of PIDs to active TCP/UDP connections. Built to understand how the Linux kernel exports networking state to user-space.
