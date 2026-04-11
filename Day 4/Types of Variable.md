# 📘 Types of Variable

---

## 🔍 Based on Scope (Visibility)

- 📌 Local Variable  
- 🌍 Global Variable  
    - ⚡ Static Variable  
    - 🔄 Non-Static Variable  

---

## 📌 Local Variable

👉 The variable declared inside a method block or any other block (except the class block) is known as a **Local Variable**.

### ✨ Characteristics of Local Variable

- 🔒 Can be accessed only inside the block where it is declared  
- 🚫 Cannot have more than one local variable with the same name inside the same block  
- 🔁 Can have the same variable name in different blocks  
- ⚠️ Must be initialized before use  

### 💻 Example

```java
public class Local_Variable {
    public static void main(String[] args) {
        int a = 10;   // Local variable
        System.out.println(a);
    }
}
```

---

## 🌍 Global Variable

👉 Variables that are directly declared inside the class block  

---

## ⚡ Static Variable

👉 Prefixed with the `static` keyword  

---

## 🔄 Non-Static Variable

👉 Not prefixed with the `static` keyword  

### 💻 Example

```java
public class Global_Variable {
    static int a = 10;  // Static variable                  
    int b = 20;        // Non-static variable

    public static void main(String[] args) {
        int a = 10;   // Local variable
        System.out.println(a);
    }
}
```

---
