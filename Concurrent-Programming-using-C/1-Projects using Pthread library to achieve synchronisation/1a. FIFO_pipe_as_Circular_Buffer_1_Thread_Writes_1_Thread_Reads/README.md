# Multithreaded 1-way, circular, FIFO pipe


<p align="center">
  <img src="imgs/screenshot.png" alt="Screenshot" width="250"/>
</p>
!\[image](ring_buffer.png)



* 1-way FIFO pipe, where 1 Thread writes and 1 reads simultaneously and circularly.
* The implemented functions are **pipe_init(), pipe_write(), pipe_read(), pipe_close()**
* If the FIFO is full, pipe\_write() blocks until data are read from FIFO
* If the FIFO is full, pipe\_read() blocks until data are written in FIFO
* The FIFO is written down in a circular way.
