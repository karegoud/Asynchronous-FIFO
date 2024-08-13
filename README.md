# Asynchronous-FIFO
1.asyncfifo.v is a top level module in which all sub module are instantiated.<br>
2.fifmem.v is a fifo memory buffer which is a dual pot RAM.
3.r2w_sync.v file has code for synchronising read pointer to write clock domain.
4.w2r_sync.v file has code for synchronising write pointer to read clock domain.
5.rptr_empty.v contains logic to generate empty signal based on read pointer and synchronised write pointer.
6.wptr_full.v contains logic to generate full signal based on write pointer and synchronised read pointer.
7.tb_async_fifo.v is testbench used for verifying the design of asynchrounous fifo.
