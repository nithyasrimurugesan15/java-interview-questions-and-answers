# 🔹 SECTION 5: ARRAYS CLASS (java.util.Arrays)

---

## 1️⃣ **What is Arrays class in Java?**

**A:** Arrays is a utility class in java.util package that provides methods to manipulate arrays such as sorting, searching, and copying.

---

## 2️⃣ **Why is Arrays class final?**

**A:** Arrays class is final to prevent inheritance and ensure its utility methods are not overridden.

---

## 3️⃣ **Why all methods in Arrays class are static?**

**A:** Because Arrays is a utility class and its methods can be used without creating an object.

---

## 4️⃣ **How does Arrays.sort() work internally?**

**A:** It uses Dual-Pivot QuickSort for primitives and TimSort for objects.

---

## 5️⃣ **Difference between sorting primitives vs objects?**

**A:** Primitives use QuickSort, while objects use TimSort which is stable.

---

## 6️⃣ **What is time complexity of sorting?**

**A:** Average and best case is O(n log n).

---

## 7️⃣ **What is Arrays.binarySearch()?**

**A:** It is a method used to search an element in a sorted array using binary search.

---

## 8️⃣ **What is prerequisite for binarySearch()?**

**A:** The array must be sorted before calling binarySearch().

---

## 9️⃣ **What happens if array is not sorted before binarySearch()?**

**A:** The result will be incorrect or unpredictable.

---

## 🔟 **Why Arrays.asList() fails for primitive arrays?**

**A:** Because it treats the entire primitive array as a single object instead of individual elements.

---

## 1️⃣1️⃣ **Difference between equals() and deepEquals()?**

**A:** equals() compares references or shallow values, while deepEquals() compares nested array contents.

---

## 1️⃣2️⃣ **What is Arrays.copyOf()?**

**A:** It creates a new array by copying elements from an existing array.

---

## 1️⃣3️⃣ **Difference between copyOf() and copyOfRange()?**

**A:** copyOf() copies entire array, while copyOfRange() copies a specific range.

---

## 1️⃣4️⃣ **What is Arrays.fill()?**

**A:** It is used to fill an array with a specific value.

---

## 1️⃣5️⃣ **What is Arrays.toString()?**

**A:** It converts an array into a readable string format.

---

## 1️⃣6️⃣ **What is Arrays.compare()?**

**A:** It compares two arrays lexicographically.

---

## 1️⃣7️⃣ **What is Arrays.mismatch()?**

**A:** It finds the first index where two arrays differ.

---

## 1️⃣8️⃣ **What is Arrays.parallelSort()?**

**A:** It sorts arrays using parallel processing for better performance.

---

## 1️⃣9️⃣ **When should you use parallelSort()?**

**A:** For large arrays where multi-threading improves performance.

---

## 2️⃣0️⃣ **What is Arrays.stream()?**

**A:** It converts an array into a stream for functional operations.

---
