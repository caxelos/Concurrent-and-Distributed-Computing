# Concurrent Programming techniques using C and pThreads library
<p align="left">
  <img src="../imgs/concurrent_programming.png" alt="???" width="600" height="400"/>
</p>

* Folder "**Concurrent-Programming-using-C**" contains several projects that implement several concurrent programming mechanisms like ***Semaphores, Mutexes, Synchronization, Critical Code Sections (CSS)***.
* All of these are implemented in **C language** from scratch, using ***Linux P-threads, OpenMP and CUDA***.
* From Technical Perspective, we:
  - Use Pthread library to implement **mutexes** from scratch.
  - Pthread library to implement **fair binary semaphores** from scratch.
  - Pthread library in order to implement Condition Monitors and wait mechanisms.
  - We also implement a compound project (Compiler Parser), in order to combine and get familiar with these techniques.
* The list of projects are the following:
    - **Circular read/write FIFO buffer** (one thread writes and one thread reads, both asynchronously).
    - Recursive, concurrent **Mandelbrot pattern production**.
    - **Recursive Quicksort**.
    - **Multithreaded compiler parsing**, error checking and execution of AT-Command based instructions (pseudo script language).
