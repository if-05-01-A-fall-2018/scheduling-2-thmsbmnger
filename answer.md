# Scheduling 2

#### 1.
The process will be swapped five times.
| Run | 1st run | 2nd run | 3rd run | 4th run | 5th run |
|:---:|:-------:|:-------:|:-------:|:-------:|:-------:|
|  Q  |    1    |    2    |    4    |    8    |    15   |
| Acc |    1    |    3    |    7    |    15   |    30   |
---
#### 2.
With the assumption that the processes A and B have the same initial estimate:

    Process A: 50 / 16 + 150 /8 + 300 / 4 + 85 / 2 = 139.375 msec
    Process B: 300 / 16 + 150 / 8 + 85 / 4 + 50 / 2 = 83.75 msec
**Conclusion:**
Process B will be scheduled.

---
#### 3.
CPU-bound:
    
    A CPU-bound process is a process, that spends the majority of its time using the CPU (calculations)
    Example: Calculating the next biggest prime number

I/O-bound:

    A I/O-bound process is a process, that spends the majority of its time using I/O-components 
    Example: Clicking stuff on a website
  
The scheduler needs to know if a process is I/O- or CPU-bound because most I/O-bound processes wait for input. If you would give the I/O bound processes a high quanta the response time of those processes would be to high. 

---
#### 4

250 msec??  
because 250 / 250 <= 1
