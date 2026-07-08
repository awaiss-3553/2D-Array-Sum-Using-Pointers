# 2D Array Sum Using Pointers

## 🎯 Objective
Calculate the sum of all elements in a 2D array using pointer-to-pointer notation.

## 🔍 Key Concepts
- **Pointer to Pointer**: `*(*(arr + i) + j)`
- **2D Array Memory Layout**: Row-major order
- **Array Decay**: 2D arrays decay to pointer to array
- **Dynamic 2D Arrays**: Using `new` for dynamic allocation

## 🧮 Algorithm
1. For each row:
   - For each column:
     - Access element using `*(*(arr + i) + j)`
     - Add to running sum
2. Return total sum

## 💻 Sample Input/Output
