# 🔹 SECTION 2: INTERMEDIATE ARRAY CONCEPTS

---

## 1️⃣ **How are arrays passed to methods in Java?**

**A:** Arrays are passed as references by value, meaning a copy of the reference is passed, but both refer to the same array object.

---

## 2️⃣ **Is Java pass-by-value or pass-by-reference for arrays?**

**A:** Java is always pass-by-value, but for arrays, the reference is passed by value, so changes affect the original array.

---

## 3️⃣ **Can a method return an array?**

**A:** Yes, a method can return an array by returning the array reference.

---

## 4️⃣ **How are arrays stored in heap memory?**

**A:** Arrays are objects stored in heap memory, and each element is stored in contiguous memory locations.

---

## 5️⃣ **What happens internally when array is created?**

**A:** Memory is allocated in heap, default values are assigned, and a reference is returned.

---

## 6️⃣ **Can arrays store objects? How?**

**A:** Yes, arrays can store objects by storing references to those objects.

---

## 7️⃣ **Difference between shallow copy and deep copy of arrays?**

**A:** Shallow copy copies references, while deep copy creates a new array with independent elements.

---

## 8️⃣ **How to clone an array?**

**A:** Using `arr.clone()` method or `System.arraycopy()`.

---

## 9️⃣ **Difference between clone() and System.arraycopy()?**

**A:** clone() creates a new array object, while System.arraycopy() copies elements into an existing array.

---

## 🔟 **What is array covariance in Java?**

**A:** Array covariance allows assigning a subclass array to a superclass array reference.

---

## 1️⃣1️⃣ **Can arrays be generic in Java? Why not?**

**A:** No, arrays cannot be generic because they are type-safe at runtime, while generics are type-safe at compile time.

---

## 1️⃣2️⃣ **What is memory layout of arrays?**

**A:** Arrays are stored as continuous memory blocks with fixed size and indexed access.

---

## 1️⃣3️⃣ **What happens when array size is too large?**

**A:** It may throw OutOfMemoryError if sufficient memory is not available.

---

## 1️⃣4️⃣ **How does JVM optimize array access?**

**A:** JVM uses direct index access and efficient memory addressing for fast performance.

---

## 1️⃣5️⃣ **Why array index starts from 0?**

**A:** Because the index represents offset from the starting memory location, making access efficient.

---
