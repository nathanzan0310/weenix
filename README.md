# weenix

I developed a complete operating system kernel, based on Unix, as a semester-long project in CS 1690 (Operating Systems) at Brown University. Please be aware that this repository serves only as a placeholder without any code to respect Brown's academic policies. Feel free to reach out to me at nathan_an@brown.edu if you would like to see the code! Below are the project components in order of completion.

**Processes**: threads, processes, and synchronization primitives support <br>
**Drivers**: Implemented device drivers for terminals, disks, and memory devices /dev/zero and /dev/null <br>
**Virtual File System (VFS)**: a polymorphic interface between the operating systems kernel and the various file systems like S5FS, device drivers <br>
**System V File System (S5FS)**: a file system based on original Unix file system. Utilized superblock, inodes, and data blocks, ensuring efficient storage and retrieval of file system metadata and contents. Integrated Weenix VM caching system for optimized block read/write operations, <br>
**Virtual Machine**: Userspace address space management, running user-level code, servicing system calls, virtual memory maps, handling page faults, memory management via anonymous objects and shadow objects, and system calls (fork syscall) <br>
