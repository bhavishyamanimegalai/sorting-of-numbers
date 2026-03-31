# sorting-of-numbers
## Aim
To write and execute an Assembly Language Program for sorting data in Ascending and  descending order using 8051 microcontroller on Keil software.
---

## Apparatus Required
- Personal Computer  
- Keil µVision software  
---

## Algorithm(ASCENDING ORDER)
1. Initialize the register **R7** with count (number of elements).  
2. Get the first two elements into two registers.  
3. Compare the two elements:  
   - If the value in register **R0** is lower, exchange **A** and **R0** data.  
   - Otherwise, increment pointer and decrement register **R7**.  
4. Check if **R7 = 0** → if yes, move the register **R0 & A**.  
5. Increment pointer and decrement **R7**.  
6. If **R7 ≠ 0**, repeat from Step 2.  
7. Otherwise, stop the program.  
---

## Program (Ascending order)
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/a9169382-60b4-4769-8ef4-c8d3353e83c5" />

```asm




```
## OUTPUT(Ascending order)

<img width="1080" height="535" alt="image" src="https://github.com/user-attachments/assets/256f1d44-ff67-4bef-bebf-d264a6b9de27" />


---

## Algorithm(Descending order)
1. Initialize the register **R7** with count.  
2. Get first two elements in two registers.  
3. Compare the two elements of data:  
   - If the value of **R0** register is high, then exchange **A** and **R0** data.  
   - Else, increment pointer and decrement register **R7**.  
4. Check if **R7 = 0**, then move the contents of **R0** and **A**.  
5. Again increment pointer and decrement **R7**.  
6. Check if **R7 = 0**:  
   - If **No**, repeat the process from Step 2.  
   - If **Yes**, stop the program.  
---
## Program (Descending order)

```asm
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/fb7a2f49-fbb9-407f-96dc-b84fe8c5723d" />




```
## OUTPUT(Descending order)

<img width="1080" height="641" alt="image" src="https://github.com/user-attachments/assets/df48db8e-271c-4322-b154-f85b327f0192" />



---
## RESULT:
Thus the sorting of given data was done using 8051 keil software.

