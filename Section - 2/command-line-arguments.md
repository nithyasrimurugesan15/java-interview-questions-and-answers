# 🔰 Command Line Arguments — Interview Questions and Answers

---

## 1️⃣ **What are command-line arguments in Java?**

**A:** Command-line arguments are inputs passed to a Java program at the time of execution through the command line.

---

## 2️⃣ **How does JVM pass command-line arguments?**

**A:** JVM passes command-line arguments as an array of Strings to the main method parameter `String[] args`.

---

## 3️⃣ **Where are command-line arguments stored?**

**A:** They are stored in the `String[] args` array of the main method.

---

## 4️⃣ **Why are command-line arguments useful?**

**A:** They allow dynamic input to programs without modifying the source code.

---

## 5️⃣ **What happens if no command-line arguments are passed?**

**A:** The `args` array is created with length 0.

---

## 6️⃣ **Which exception occurs when accessing args without input?**

**A:** ArrayIndexOutOfBoundsException occurs when accessing a non-existing index.

---

## 7️⃣ **Why does ArrayIndexOutOfBoundsException occur in args?**

**A:** Because the program tries to access an index that does not exist in the args array.

---

## 8️⃣ **How can we prevent this exception?**

**A:** By checking `args.length` before accessing elements.

---

## 9️⃣ **Can we pass integer values as command-line arguments?**

**A:** Yes, but they are received as Strings and must be converted.

---

## 🔟 **How do we convert command-line arguments to integers?**

**A:** By using methods like `Integer.parseInt(args[i])`.

---

## 1️⃣1️⃣ **What happens if parsing fails?**

**A:** It throws a NumberFormatException.

---

## 1️⃣2️⃣ **What is difference between Scanner and command-line arguments?**

**A:** Scanner reads input during runtime, while command-line arguments are passed before program execution.

---

## 1️⃣3️⃣ **Which is better for automation: Scanner or command-line?**

**A:** Command-line arguments are better for automation.

---

## 1️⃣4️⃣ **Is main(String[] args) mandatory?**

**A:** Yes, it is required as the entry point for program execution.

---

## 1️⃣5️⃣ **Can we change the name of args variable?**

**A:** Yes, the variable name can be changed, but its type must remain `String[]`.

---

## 1️⃣6️⃣ **What happens if main method signature is changed?**

**A:** JVM will not recognize it as the entry point, and the program will not run.

---
