# 🔰 Wrapper Classes — Interview Questions and Answers

---

## 1️⃣ **What are wrapper classes in Java?**

**A:** Wrapper classes are classes that convert primitive data types into objects, such as Integer for int and Double for double.

---

## 2️⃣ **Why wrapper classes are needed?**

**A:** Wrapper classes are needed because Java collections and frameworks work only with objects, not primitive types.

---

## 3️⃣ **What is autoboxing?**

**A:** Autoboxing is the automatic conversion of primitive data types into their corresponding wrapper objects.

---

## 4️⃣ **What is unboxing?**

**A:** Unboxing is the automatic conversion of wrapper objects into their corresponding primitive data types.

---

## 5️⃣ **What is Integer caching?**

**A:** Integer caching is a mechanism where values between -128 and 127 are cached and reused to improve performance.

---

## 6️⃣ **Difference between parseInt() and valueOf()?**

**A:** parseInt() returns a primitive int, while valueOf() returns an Integer object.

---

## 7️⃣ **Difference between == and equals() in wrapper classes?**

**A:** == compares object references, while equals() compares actual values.

---

## 8️⃣ **Can wrapper objects be null?**

**A:** Yes, wrapper objects can be null because they are objects.

---

## 9️⃣ **Why wrapper classes are slower than primitives?**

**A:** Wrapper classes are slower because they involve object creation and additional memory overhead.

---

## 🔟 **What happens internally during autoboxing?**

**A:** Java internally calls methods like Integer.valueOf() to convert primitives into wrapper objects.

---

## 1️⃣1️⃣ **List all wrapper classes in Java.**

**A:** Byte, Short, Integer, Long, Float, Double, Character, Boolean.

---

## 1️⃣2️⃣ **Common methods of wrapper classes?**

**A:** parseX(), valueOf(), toString(), compareTo().

---

## 1️⃣3️⃣ **What is immutability in wrapper classes?**

**A:** Wrapper class objects are immutable, meaning their values cannot be changed once created.

---

## 1️⃣4️⃣ **When should we avoid wrapper classes?**

**A:** We should avoid wrapper classes in performance-critical applications where primitives are sufficient.

---

## 1️⃣5️⃣ **Can unboxing cause an exception?**

**A:** Yes, unboxing a null object will cause a NullPointerException.

---
