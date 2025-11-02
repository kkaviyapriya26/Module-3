# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
REG NO- 212223060120
NAME-KAVIYA PRIYA K
def slice(x):
    print(f"The reversed string is '{x[9:1:-2]}'")

```

### OUTPUT

<img width="943" height="228" alt="image" src="https://github.com/user-attachments/assets/c9ac8005-bb5e-42d2-964b-7cb5fbaba99e" />


### RESULT
Thus Python function that accepts a string and forms a new string by reversing the characters from the 4th position to the 10th position with alternate characters, and then prints the new string is implemented and sucessfully verified

