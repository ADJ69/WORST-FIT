# 🗂️ Worst Fit Memory Allocation in C

This project implements the **Worst Fit Memory Allocation** strategy in C.  
In Worst Fit, each process is allocated to the **largest available block** that can fit it.  
This helps reduce the chance of creating very small unusable fragments.

---

## 📌 Features
- Takes **memory block sizes** and **process sizes** as input  
- Allocates processes to memory using **Worst Fit** strategy  
- Displays which process is allocated to which block  

---

## 🛠 How to Run
1. Save as `WorstFit.c`
2. Compile:
   ```bash
   gcc WorstFit.c -o worstfit
