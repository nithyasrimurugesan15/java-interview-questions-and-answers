# 🔹 SECTION 6: FINAL ARRAYS

---

## 1️⃣ **What does final mean in Java?**

**A:** The final keyword is used to restrict modification, meaning the variable reference cannot be changed once assigned.

---

## 2️⃣ **What is a final array?**

**A:** A final array is an array whose reference cannot be reassigned after initialization.

---

## 3️⃣ **Can you modify elements of a final array?**

**A:** Yes, the elements of a final array can be modified.

---

## 4️⃣ **Can you reassign a final array?**

**A:** No, the reference of a final array cannot be reassigned.

---

## 5️⃣ **Difference between final array and immutable array?**

**A:** A final array restricts reference change, while an immutable array prevents modification of its elements.

---

## 6️⃣ **Why Java allows modification inside final array?**

**A:** Because final applies only to the reference, not to the internal elements.

---

## 7️⃣ **What happens if you reassign final array?**

**A:** It results in a compile-time error.

---

## 8️⃣ **Can final array be uninitialized?**

**A:** Yes, but it must be initialized before use.

---

## 9️⃣ **How is memory managed in final array?**

**A:** Memory is allocated in heap, and only the reference is fixed in stack.

---

## 🔟 **Can final array be passed to method and modified?**

**A:** Yes, elements can still be modified inside methods.

---

## 1️⃣1️⃣ **Difference between final object and final array?**

**A:** Both prevent reference reassignment, but internal data can still be modified unless explicitly restricted.

---

## 1️⃣2️⃣ **Is final array thread-safe?**

**A:** No, because elements can still be modified by multiple threads.

---

## 1️⃣3️⃣ **How to make array truly immutable?**

**A:** By not exposing it directly and returning a copy instead.

---

## 1️⃣4️⃣ **What is static final array?**

**A:** A static final array is shared across all instances and its reference cannot be changed.

---

## 1️⃣5️⃣ **When should final arrays be used?**

**A:** When you want a constant reference but allow modification of elements.

---
