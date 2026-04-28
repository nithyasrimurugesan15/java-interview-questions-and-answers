# 🔰 Varargs — Interview Questions and Answers

---

## 1️⃣ **What are varargs in Java?**

**A:** Varargs (variable arguments) allow a method to accept zero or more arguments of the same type.

---

## 2️⃣ **Why were varargs introduced?**

**A:** Varargs were introduced to simplify method calls that require a variable number of arguments.

---

## 3️⃣ **What problems existed before varargs?**

**A:** Before varargs, we had to use arrays or create multiple overloaded methods to handle different numbers of arguments.

---

## 4️⃣ **How are varargs implemented internally?**

**A:** Varargs are internally treated as arrays by the Java compiler.

---

## 5️⃣ **Can we pass zero arguments in varargs?**

**A:** Yes, varargs can accept zero arguments.

---

## 6️⃣ **What is the type of varargs inside a method?**

**A:** Inside the method, varargs are treated as an array.

---

## 7️⃣ **What are the rules of varargs?**

**A:** Only one varargs parameter is allowed, and it must be the last parameter in the method.

---

## 8️⃣ **Why only one varargs parameter is allowed?**

**A:** Because multiple varargs parameters would create ambiguity in method calls.

---

## 9️⃣ **Why must varargs be the last parameter?**

**A:** To avoid confusion in argument matching during method calls.

---

## 🔟 **What error occurs if varargs is not the last parameter?**

**A:** It results in a compile-time error.

---

## 1️⃣1️⃣ **What is difference between varargs and arrays?**

**A:** Varargs provide flexible arguments in method calls, while arrays require explicit creation and passing.

---

## 1️⃣2️⃣ **When should we use varargs?**

**A:** When the number of inputs to a method is not fixed.

---

## 1️⃣3️⃣ **When should we prefer arrays over varargs?**

**A:** When we already have data in array form or need more control over data.

---

## 1️⃣4️⃣ **What is difference between varargs and method overloading?**

**A:** Varargs allow variable inputs in a single method, while overloading uses multiple methods for different parameter counts.

---

## 1️⃣5️⃣ **Which is better: varargs or overloading?**

**A:** Varargs are better for flexible inputs, while overloading is better when logic differs for each case.

---

## 1️⃣6️⃣ **Can we overload varargs methods?**

**A:** Yes, but it can lead to ambiguity if not used carefully.

---

## 1️⃣7️⃣ **What ambiguity issues occur in varargs overloading?**

**A:** The compiler may not determine which method to call if multiple varargs methods match the same arguments.

---
