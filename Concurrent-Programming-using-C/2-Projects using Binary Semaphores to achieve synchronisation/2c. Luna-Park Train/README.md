# Luna Park train project using fair binary Semaphores

<p align="left">
  <img src="../../../imgs/luna_park_train.png" alt="???" width="700" height="700"/>
</p> 

1. Each person is a thread. The wagon is also a thread (the main thread of the application).
2. Luna Park train requirements:
	- The train wagon can hold N persons.
	- The wagon begins only when it's full.
	- The passengers get out of the train, only when it has reached the finish point.
	- New passengers can onboard only when the wagon is empty again.

2. When each person arrives at a wagon, a new thread is created...
	- Similarly, when a person gets out of the wagon, a thread is terminated.
