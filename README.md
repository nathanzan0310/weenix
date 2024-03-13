# weenix

Developed a complete operating system kernel, based on Unix, as a semester-long project in CS 1690 (Operating Systems) at Brown University. Below are the project components in order of completion.

Processes: threads, processes, and synchronization primitives support <br>
Drivers: Implemented device drivers for terminals, disks, and memory devices /dev/zero and /dev/null <br>
Virtual File System (VFS): a polymorphic interface between the operating systems kernel and the various file systems like S5FS, device drivers
System V File System (S5FS): a file system based on original Unix file system. Utilized superblock, inodes, and data blocks, ensuring efficient storage and retrieval of file system metadata and contents. Integrated Weenix VM caching system for optimized block read/write operations,
Virtual Machine: Userspace address space management, running user-level code, servicing system calls, virtual memory maps, handling page faults, memory management via anonymous objects and shadow objects, and system calls (fork syscall)

NOTE: This is a placeholder repo with no code to respect Brown's Academic Code. If you are a potential employer and would like to look at the code, please send me an email.
