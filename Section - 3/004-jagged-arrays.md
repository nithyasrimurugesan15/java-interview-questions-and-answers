# 🔹 SECTION 4: JAGGED ARRAYS

---

## 1️⃣ **What is a jagged array?**

**A:** A jagged array is an array of arrays where each inner array can have a different length.

---

## 2️⃣ **How is jagged array different from 2D array?**

**A:** In a jagged array, rows can have different sizes, while in a regular 2D array all rows have the same size.

---

## 3️⃣ **Why Java supports jagged arrays?**

**A:** Java treats multi-dimensional arrays as arrays of arrays, which allows flexible memory allocation.

---

## 4️⃣ **How is memory allocated in jagged arrays?**

**A:** Memory is allocated separately for each inner array instead of a continuous block.

---

## 5️⃣ **How to declare and initialize jagged arrays?**

**A:** Jagged arrays are declared and initialized like this:


int[][] arr = new int[3][];
arr[0] = new int[2];
arr[1] = new int[4];
arr[2] = new int[3];

---

## 📌 Jagged Arrays (Quick Preview)

### 6️⃣ How to traverse jagged arrays safely?
**A:** By using nested loops and accessing each row using `arr[i].length`.

### 7️⃣ What happens if inner arrays are not initialized?
**A:** It throws a NullPointerException when accessed.

### 8️⃣ What are advantages of jagged arrays?
**A:** Better memory utilization and flexibility for irregular data.

### 9️⃣ What are disadvantages of jagged arrays?
**A:** More complex to manage and less predictable structure.

### 🔟 When should jagged arrays be used?
**A:** When data rows have varying sizes.

### 1️⃣1️⃣ When should jagged arrays be avoided?
**A:** When a uniform structure is required.

### 1️⃣2️⃣ How jagged arrays are used in graph representation?
**A:** They are used to implement adjacency lists where each node has different number of connections.

### 1️⃣3️⃣ Difference between jagged array and ArrayList of ArrayList?
**A:** Jagged arrays have fixed size, while ArrayList is dynamic and resizable.

### 1️⃣4️⃣ Are jagged arrays cache friendly? Why?
**A:** No, because memory is not contiguous.

### 1️⃣5️⃣ Can jagged arrays improve performance?
**A:** Yes, when used for irregular data, they reduce unnecessary memory usage.

