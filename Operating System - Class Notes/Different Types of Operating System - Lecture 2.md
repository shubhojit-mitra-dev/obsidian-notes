🎓  Course: [[Operating System]]

📖  Topic: #typesofos

📆  Date: 2024-08-06

🏷️  Labels: #typesofos #lecture2 #batchos

🔗  Important Links: 

---

```
We assume that the system is a uni-processor system
```

### 1. Batch OS:

This Operating system performed on batch processes. 
A **batch** is a set of similar tasks.

**The Limitation** of Batch Operating System:
- It would **perform jobs only of similar nature (considering them as a batch)**. 
- It only takes **one job at a time (One batch at a time)**. 
- Allocates all the resources to the picked job.

---
### 2. Multi-programming OS:

As the name goes **Multiple programs at the same time**

![[Pasted image 20240806144409.png]]

**In the Batch OS the I/O Burst will let the CPU to be Idle**

In Multi-programming OS, at the time of I/O Burst, If Process P1, is in I/O Burst the CPU will be allocated to the P2. 

**The Limitation of Multi-programming OS**:
- The allocation of the CPU resources is in the hands of the OS.
- User cannot choose the process to be executed during the I/O Burst of P1.

Any process is either:
- **CPU BOUND**
- **I/O BOUND**

---
### 3. Multi-tasking OS:

The users can choose the programs to be executed. User intervention is allowed making the CPU utilization more efficient.