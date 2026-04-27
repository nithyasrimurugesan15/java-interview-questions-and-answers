# 🔰 JVM, JRE, JDK — Interview Questions and Answers

---

## 1️⃣ **What is JVM?**

**A:** JVM (Java Virtual Machine) is a runtime environment that executes Java bytecode and converts it into machine code for execution on the system.

---

## 2️⃣ **What is JRE?**

**A:** JRE (Java Runtime Environment) provides the necessary libraries and JVM required to run Java programs.

---

## 3️⃣ **What is JDK?**

**A:** JDK (Java Development Kit) is a complete development package that includes JRE and tools like compiler (javac), debugger, and utilities to develop Java applications.

---

## 4️⃣ **Difference between JVM, JRE, and JDK?**

**A:**
JVM → Executes bytecode
JRE → Provides runtime environment (JVM + libraries)
JDK → Provides development tools (JRE + compiler and tools)

---

## 5️⃣ **Why JVM is platform-dependent but Java is platform-independent?**

**A:** JVM is platform-dependent because it is implemented differently for each operating system, but Java bytecode remains the same across platforms, making Java platform-independent.

---

## 6️⃣ **What are the components of JVM?**

**A:** The main components of JVM are Class Loader, Method Area, Heap Memory, Stack Memory, Program Counter Register, Native Method Stack, and Execution Engine.

---

## 7️⃣ **What is Class Loader?**

**A:** Class Loader is a subsystem of JVM that loads class files into memory at runtime.

---

## 8️⃣ **What is bytecode verification?**

**A:** Bytecode verification is the process of checking the correctness and security of bytecode before execution.

---

## 9️⃣ **What is Garbage Collection?**

**A:** Garbage Collection is the automatic process of removing unused objects from memory to free up space.

---

## 🔟 **Interpreter vs JIT Compiler?**

**A:** Interpreter executes bytecode line by line, while JIT compiler converts frequently used bytecode into native machine code to improve performance.

---

## 1️⃣1️⃣ **Can Java run without JVM?**

**A:** No, Java programs cannot run without JVM because JVM is required to execute the bytecode.

---

## 1️⃣2️⃣ **Why JDK includes JRE?**

**A:** JDK includes JRE because development requires both compiling and running Java programs.

---

## 1️⃣3️⃣ **Explain Java execution flow step-by-step.**

**A:** A Java program is written in a .java file, compiled into bytecode using javac, then the JVM loads the class, verifies the bytecode, and executes it using interpreter or JIT compiler.

---

## 1️⃣4️⃣ **What is Execution Engine in JVM?**

**A:** Execution Engine is the part of JVM that executes bytecode using interpreter and JIT compiler.

---

## 1️⃣5️⃣ **What is Method Area in JVM?**

**A:** Method Area stores class-level data such as class metadata, static variables, and method information.

---

## 1️⃣6️⃣ **What is Heap Memory?**

**A:** Heap Memory is used to store objects and is managed by garbage collection.

---

## 1️⃣7️⃣ **What is Stack Memory?**

**A:** Stack Memory is used to store method calls, local variables, and function execution data.

---

## 1️⃣8️⃣ **What is Program Counter Register?**

**A:** Program Counter Register holds the address of the current executing instruction.

---

## 1️⃣9️⃣ **What is Native Method Stack?**

**A:** Native Method Stack is used to execute native methods written in languages like C or C++.

---

## 2️⃣0️⃣ **Why is JVM important?**

**A:** JVM is important because it enables platform independence, manages memory, ensures security, and executes Java programs efficiently.

---
