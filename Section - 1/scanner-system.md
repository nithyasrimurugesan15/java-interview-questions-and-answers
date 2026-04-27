# 🔰 Scanner Class — Interview Questions and Answers

---

## 1️⃣ **What is Scanner class in Java?**

**A:** Scanner is a class in the java.util package used to read input from various sources such as keyboard, files, or input streams.

---

## 2️⃣ **Why Scanner is preferred over BufferedReader?**

**A:** Scanner is preferred because it can directly read and parse primitive data types like int, double, and String, whereas BufferedReader reads only text and requires manual parsing.

---

## 3️⃣ **How does Scanner work internally?**

**A:** Scanner reads input as text and uses regular expressions to break it into tokens and convert them into required data types.

---

## 4️⃣ **Difference between next() and nextLine()?**

**A:** next() reads input until a space (single word), while nextLine() reads the entire line including spaces until a newline character.

---

## 5️⃣ **Why nextInt() followed by nextLine() causes issues?**

**A:** nextInt() reads only the integer and leaves the newline character in the buffer, so nextLine() reads that leftover newline instead of actual input.

---

## 6️⃣ **How to fix Scanner input issue?**

**A:** Add an extra nextLine() after nextInt() to consume the leftover newline character.

---

## 7️⃣ **Is Scanner thread-safe?**

**A:** No, Scanner is not thread-safe.

---

## 8️⃣ **Why Scanner is slower compared to BufferedReader?**

**A:** Scanner is slower because it uses regular expressions and parsing internally, which adds overhead.

---

## 9️⃣ **When to use BufferedReader instead of Scanner?**

**A:** BufferedReader should be used when fast input reading is required, especially in competitive programming.

---

## 🔟 **What happens on invalid input?**

**A:** Scanner throws InputMismatchException when the input type does not match the expected data type.

---

## 1️⃣1️⃣ **Can Scanner read from files?**

**A:** Yes, Scanner can read input from files, input streams, and strings.

---

## 1️⃣2️⃣ **Which package does Scanner belong to?**

**A:** Scanner belongs to the java.util package.

---

## 1️⃣3️⃣ **Do we need to close Scanner?**

**A:** Yes, Scanner should be closed using close() to prevent resource leaks.

---

## 1️⃣4️⃣ **What is delimiter in Scanner?**

**A:** Delimiter is a pattern used to separate input tokens, and by default it is whitespace.

---

## 1️⃣5️⃣ **Can we change delimiter in Scanner?**

**A:** Yes, using useDelimiter() method we can change the delimiter.

---
