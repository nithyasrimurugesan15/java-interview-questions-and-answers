# 🔥 SECTION 7: ADVANCED / TRICKY ARRAY QUESTIONS

---

## 1️⃣ **Why arrays are faster than ArrayList?**

**A:** Arrays are faster because they use direct memory access without additional overhead like resizing and method calls.

---

## 2️⃣ **Why arrays are not part of Java Collections Framework?**

**A:** Arrays were introduced before collections and are built-in language structures, not part of the framework.

---

## 3️⃣ **Can we override array behavior in Java?**

**A:** No, arrays are fixed structures and cannot be overridden.

---

## 4️⃣ **What happens when array is created but not initialized?**

**A:** The array elements are automatically assigned default values.

---

## 5️⃣ **Difference between int[] arr and int arr[]?**

**A:** Both are syntactically valid and equivalent, but int[] arr is preferred for clarity.

---

## 6️⃣ **Can arrays store heterogeneous data?**

**A:** No, arrays can store only elements of the same data type.

---

## 7️⃣ **Why arrays are not dynamic in Java?**

**A:** Because their size is fixed at creation and cannot be resized.

---

## 8️⃣ **What is memory fragmentation in arrays?**

**A:** It is the inability to allocate a large contiguous memory block even if total memory is sufficient.

---

## 9️⃣ **How does JVM perform bounds checking?**

**A:** JVM checks index at runtime and throws ArrayIndexOutOfBoundsException if invalid.

---

## 🔟 **Why arrays are considered low-level data structures?**

**A:** Because they provide direct memory access with minimal abstraction.

---

## 1️⃣1️⃣ **Can we synchronize arrays?**

**A:** Arrays themselves cannot be synchronized, but we can synchronize access using synchronization mechanisms.

---

## 1️⃣2️⃣ **What is false sharing in arrays?**

**A:** It occurs when multiple threads access nearby memory locations, causing performance degradation due to cache conflicts.

---

## 1️⃣3️⃣ **How arrays impact CPU cache performance?**

**A:** Arrays improve cache performance due to contiguous memory storage.

---

## 1️⃣4️⃣ **What are alternatives to arrays in Java?**

**A:** ArrayList, LinkedList, and other collections.

---

## 1️⃣5️⃣ **When arrays become bottleneck in system design?**

**A:** When dynamic resizing, flexibility, or frequent insertions/deletions are required.

---
