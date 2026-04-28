# 🔰 Static vs Instance Methods

---

## 2️⃣5️⃣ **What is a static method in Java?**

**A:** A static method belongs to the class and can be called without creating an object.

---

## 2️⃣6️⃣ **What is an instance method in Java?**

**A:** An instance method belongs to an object and requires object creation to be called.

---

## 2️⃣7️⃣ **Difference between static and instance methods?**

**A:** Static methods belong to class, while instance methods belong to objects.

---

## 2️⃣8️⃣ **Why do static methods not require objects?**

**A:** Because they are associated with the class, not with individual objects.

---

## 2️⃣9️⃣ **Where are static members stored in memory?**

**A:** Static members are stored in the method area of memory.

---

## 3️⃣0️⃣ **Where are instance members stored in memory?**

**A:** Instance members are stored in heap memory.

---

## 3️⃣1️⃣ **Which is more memory efficient: static or instance?**

**A:** Static is more memory efficient because only one copy is shared across all objects.

---

## 3️⃣2️⃣ **When should we use static methods?**

**A:** When the method does not depend on object-specific data.

---

## 3️⃣3️⃣ **When should we use instance methods?**

**A:** When the method works on object-specific data.

---

## 3️⃣4️⃣ **Can static methods access instance variables?**

**A:** No, static methods cannot directly access instance variables.

---

## 3️⃣5️⃣ **Why static methods cannot access instance variables directly?**

**A:** Because instance variables belong to objects, while static methods belong to the class.

---

## 3️⃣6️⃣ **Can static methods access instance variables indirectly?**

**A:** Yes, by creating an object.

---

## 3️⃣7️⃣ **Why is this keyword not allowed in static methods?**

**A:** Because this refers to the current object, and static methods do not have an object context.

---

## 3️⃣8️⃣ **Can instance methods access static members?**

**A:** Yes, instance methods can access static members.

---

## 3️⃣9️⃣ **Why are instance methods allowed to access static members?**

**A:** Because static members are shared across all objects and accessible through class.

---

## 4️⃣0️⃣ **Can static methods be overridden?**

**A:** No, static methods cannot be overridden.

---

## 4️⃣1️⃣ **What is method hiding?**

**A:** Method hiding occurs when a static method in subclass has the same name as in superclass.

---

## 4️⃣2️⃣ **Difference between overriding and hiding?**

**A:** Overriding is runtime polymorphism, while hiding is compile-time behavior.

---

## 4️⃣3️⃣ **Do static methods support runtime polymorphism?**

**A:** No, static methods are resolved at compile time.

---

## 4️⃣4️⃣ **Why are static methods resolved at compile time?**

**A:** Because they belong to the class and not to objects.

---

## 4️⃣5️⃣ **What happens if we make all methods static?**

**A:** It breaks object-oriented design and removes encapsulation and polymorphism.

---

## 4️⃣6️⃣ **What OOP principles break if everything is static?**

**A:** Encapsulation, inheritance, and polymorphism.

---

## 4️⃣7️⃣ **How does excessive static usage affect scalability?**

**A:** It reduces flexibility and makes the system harder to extend.

---
