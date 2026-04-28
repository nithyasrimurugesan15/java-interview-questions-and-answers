# 🔰 Advanced & Tricky Java Interview Questions

---

## 1️⃣ **Why is Java strictly pass-by-value?**

**A:** Java is strictly pass-by-value because it always passes a copy of the variable, not the original memory reference.

---

## 2️⃣ **How does pass-by-value work with objects?**

**A:** A copy of the reference is passed, so both references point to the same object, but the reference itself cannot be changed.

---

## 3️⃣ **What is common misconception about pass-by-reference?**

**A:** Many think Java is pass-by-reference, but actually it passes object references by value.

---

## 4️⃣ **Why static methods do not support polymorphism?**

**A:** Static methods are resolved at compile time and are not associated with objects, so runtime polymorphism is not possible.

---

## 5️⃣ **What is difference between compile-time and runtime binding?**

**A:** Compile-time binding is resolved during compilation (static methods), while runtime binding is resolved during execution (instance methods).

---

## 6️⃣ **Why static methods cannot use this keyword?**

**A:** Because this refers to the current object, and static methods do not belong to objects.

---

## 7️⃣ **Can main method be non-static?**

**A:** No, JVM requires main method to be static to call it without creating an object.

---

## 8️⃣ **Why JVM requires main method to be static?**

**A:** Because JVM starts execution without creating any object, so main must be static.

---

## 9️⃣ **What happens internally when Java program runs?**

**A:** The code is compiled into bytecode, loaded by class loader, verified, and executed by JVM using interpreter and JIT compiler.

---

## 🔟 **Why Java does not support multiple inheritance with classes?**

**A:** To avoid ambiguity and complexity such as the diamond problem.

---

## 1️⃣1️⃣ **What is diamond problem?**

**A:** It occurs when a class inherits from two classes that have the same method, causing ambiguity.

---

## 1️⃣2️⃣ **How Java solves multiple inheritance?**

**A:** Java supports multiple inheritance using interfaces.

---

## 1️⃣3️⃣ **What is difference between == and equals()?**

**A:** == compares references, while equals() compares object values.

---

## 1️⃣4️⃣ **Why String is immutable?**

**A:** For security, performance, and thread safety.

---

## 1️⃣5️⃣ **What is memory leak in Java?**

**A:** Memory leak occurs when unused objects are not released, even though garbage collection exists.

---

## 1️⃣6️⃣ **How can memory leak happen in Java?**

**A:** Through static collections, unclosed resources, or lingering object references.

---

## 1️⃣7️⃣ **What is difference between stack and heap memory?**

**A:** Stack stores method calls and local variables, while heap stores objects.

---

## 1️⃣8️⃣ **Why stack memory is faster than heap?**

**A:** Because it uses simple allocation and deallocation (LIFO).

---

## 1️⃣9️⃣ **What is garbage collection?**

**A:** It is the automatic process of removing unused objects from memory.

---

## 2️⃣0️⃣ **Can we force garbage collection?**

**A:** No, we can only request it using System.gc(), but execution is not guaranteed.

---

## 2️⃣1️⃣ **What is difference between final, finally, finalize?**

**A:** final is a keyword, finally is a block, and finalize is a method used before garbage collection.

---

## 2️⃣2️⃣ **Why Java is considered secure?**

**A:** Because it avoids pointers, has bytecode verification, and runs inside JVM.

---

## 2️⃣3️⃣ **What is class loader?**

**A:** It loads class files into JVM memory during execution.

---

## 2️⃣4️⃣ **What is JIT compiler?**

**A:** It converts frequently used bytecode into native machine code for better performance.

---

## 2️⃣5️⃣ **What is difference between abstraction and encapsulation?**

**A:** Abstraction hides implementation details, while encapsulation hides data using access modifiers.

---
