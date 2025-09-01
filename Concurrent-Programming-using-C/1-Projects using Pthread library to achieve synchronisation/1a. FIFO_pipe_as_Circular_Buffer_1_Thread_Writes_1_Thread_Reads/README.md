# Multithreaded 1-way, circular, FIFO pipe



* 1-way FIFO pipe, where 1 Thread writes and 1 reads simultaneously and circularly.
* The implemented functions are \*\*pipe\_write(), pipe\_read(), 
* If the FIFO is full, pipe\_write() blocks until data are read from FIFO
* If the FIFO is full, pipe\_read() blocks until data are written in FIFO
* The FIFO is written down in a circular way.	
