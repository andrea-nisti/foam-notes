# thread states

#rtos #qnx

## blocked states

waiting for something to happen (**ignored from scheduling code**):
- *REPLY* waiting for IPC
- *MUTEX* blocked on a mutex
- *RECEIVE*  waiting to get a message
  
## runnable states 

capable of using cpu

- *RUNNING* using cpu 
- *READY* ready to be scheduled
