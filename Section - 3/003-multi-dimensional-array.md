# 🔹 SECTION 3: MULTI-DIMENSIONAL ARRAYS

---

## 1️⃣ **What is a multi-dimensional array?**

**A:** A multi-dimensional array is an array of arrays used to store data in tabular form such as rows and columns.

---

## 2️⃣ **How is a 2D array represented internally in Java?**

**A:** A 2D array is represented as an array of references, where each element points to another array.

---

## 3️⃣ **Difference between 2D array in Java vs C?**

**A:** In Java, 2D arrays are arrays of arrays (non-contiguous), while in C they are stored in contiguous memory.

---

## 4️⃣ **How to declare and initialize 2D array?**

**A:** It can be declared as `int[][] arr = new int[3][3]` or initialized as `int[][] arr = {{1,2},{3,4}}`.

---

## 5️⃣ **How to traverse a 2D array?**

**A:** By using nested loops, where the outer loop iterates rows and the inner loop iterates columns.

---

## 6️⃣ **Why use arr[i].length instead of arr[0].length?**

**A:** Because each row can have a different length in Java.

---

## 7️⃣ **What is time complexity of 2D traversal?**

**A:** O(n × m), where n is number of rows and m is number of columns.

---

## 8️⃣ **How to take input for 2D arrays?**

**A:** Using nested loops with input methods like Scanner.

---

## 9️⃣ **What is a 3D array?**

**A:** A 3D array is an array of 2D arrays used to store data in three dimensions.

---

## 🔟 **How is size calculated in multi-dimensional arrays?**

**A:** Size is calculated as rows × columns × depth depending on dimensions.

---

## 1️⃣1️⃣ **What are real-world applications of 2D arrays?**

**A:** Matrices, grids, image processing, and game boards.

---

## 1️⃣2️⃣ **What is row-major order?**

**A:** Row-major order stores elements row by row.

---

## 1️⃣3️⃣ **What is column-major order?**

**A:** Column-major order stores elements column by column.

---

## 1️⃣4️⃣ **Why row-wise traversal is faster in Java?**

**A:** Because elements are accessed in memory-friendly order, improving cache performance.

---

## 1️⃣5️⃣ **Can 2D arrays be non-rectangular?**

**A:** Yes, Java supports non-rectangular arrays (jagged arrays).

---
