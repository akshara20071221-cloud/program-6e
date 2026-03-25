# program-6e
# 🧪 C Programming Lab
## 📘 Experiment No: 6e
### 🔹
**Date:** 19/3/2026  
**Name:** AKshara.k 
**Register No:** 25003090 

---

## 🎯 AIM
To write a C program to read and display an array using pointers.
---

## 🧠 ALGORITHM
1.Get an array as input from the user using for loop.
2.Assign a pointer variable to the array.
3.Print the elements of that array using the pointer variable.
---

## 💻 PROGRAM
```
#include <stdio.h>

int main() {
    int arr[4];
    int *ptr;
    int i;

    ptr = arr;  // pointer points to the first element of the array

    // Read 4 elements
    for (i = 0; i < 4; i++) {
        scanf("%d", (ptr + i));   // read using pointer
    }

    // Display elements
    
    for (i = 0; i < 4; i++)
    {
        printf("The elements are ");
        printf("%d ", *(ptr + i));  // display using pointer
    }

    printf("\n");
    return 0;
}
```

## 🖼️ OUTPUT SCREENSHOT

<img width="592" height="308" alt="image" src="https://github.com/user-attachments/assets/467d13e7-e64b-4999-b29c-ce54e9464312" />



---

## ✅ RESULT
Thus the C program to read and display an array using pointers is executed successfully.
