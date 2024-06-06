
### Processes

###### Properties
- A set of Instructions
- Has an isolated memory (process and its children can access this memory)
- Every process has a unique identifier - **PID k/as process ID** 
- Scheduled in CPU


### Thread

###### Properties
- LWP - Light weight process
- Inherits memory from its parent (main) process
- share memory with parent process
- a set of instructions
- has a unique ID
- Scheduled in CPU


#### Multi Threaded
###### Properties
- One Process, multiple threads
- Shared memory
- Take benefits of multiple cores
- require less memory
- Race conditions
- locks and latches



### 💡 Rule of Thumb - No. of Cores should be equal to No. of Process 
