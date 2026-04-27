# 🔰 System.out.println() — Interview Questions and Answers

---

## 1️⃣ **What is System.out.println()?**

**A:** System.out.println() is a method used to print output to the console, followed by a newline.

---

## 2️⃣ **Break down System.out.println()**

**A:**
System → predefined class in java.lang
out → static PrintStream object
println() → method used to print data

---

## 3️⃣ **What is PrintStream?**

**A:** PrintStream is a class used to send output to the console or other output destinations.

---

## 4️⃣ **Difference between print() and println()?**

**A:** print() displays output without a newline, while println() displays output and moves the cursor to the next line.

---

## 5️⃣ **Can println() print all data types?**

**A:** Yes, println() can print all primitive data types and objects.

---

## 6️⃣ **What happens when an object is passed to println()?**

**A:** The println() method internally calls the toString() method of the object.

---

## 7️⃣ **Can we use println() without System?**

**A:** No, println() must be accessed through an output stream like System.out.

---

## 8️⃣ **Is System.out thread-safe?**

**A:** Yes, PrintStream methods like println() are synchronized and thread-safe.

---

## 9️⃣ **Can we redirect System.out output?**

**A:** Yes, using System.setOut() we can redirect output to a file or another stream.

---

## 🔟 **Why not use System.out.println() in production?**

**A:** It is not suitable for production because it lacks flexibility, cannot manage log levels, and affects performance. Logging frameworks are preferred.

---

## 1️⃣1️⃣ **Which package contains System class?**

**A:** System class belongs to the java.lang package.

---

## 1️⃣2️⃣ **Can we print without newline using println()?**

**A:** No, println() always prints a newline. Use print() to avoid newline.

---
