# Starve-Free-Reader-Writer-Problem
Sometimes many processes are trying to access a shared resource (a file or record, etc.) to either modify or read it. In case a process tries to write a shared resource and another tries to read it or if two processes are attempting to modify/write the same resource, then it could create a lot of errors. Readers-writers deal with this synchronization problem.
The first readers-writers problem prioritizes the reader and the writer may starve. The second one prioritizes the writer and the reader may starve. The third problem employs Queue implementation, where the processes are added to the queue if the process cannot access the shared resource.

References
Abraham Silberschatz, Peter B. Galvin, Greg Gagne - Operating System Concepts
https://arxiv.org/abs/1309.4507
https://arxiv.org/abs/cs/0303005
