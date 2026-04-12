# 📘 Typecasting

---

## 🧩 Typecasting:
It is the process of converting one datatype into another datatype

---

## 🔍 Type-casting is divided into 2 types:
- 🔢 Primitive Typecasting
- 🧱 Non-Primitive Typecasting

---

## 🔢 Primitive Typecasting:
Converting one primitive datatype into another primitive datatype

- 📈 Widening
    - ✍️ Explicit
    - ⚙️ Implicit
- 📉 Narrowing
    - ✍️ Explicit

---

## 🧱 Non-Primitive Typecasting:
Converting one nonprimitive datatype into another nonprimitive datatype

- ⬆️ Upcasting
- ⬇️ Down casting

---

## ✍️ Explicit:
If a programmer is converting then it is known as Explicit.

## ⚙️ Implicit:
If a compiler is converting then it is known as Implicit.

---

## 📈 Widening :
Converting smaller primitive datatype to higher primitive datatype is known as Widening.

```text
Byte < short / char < int < long < float < double
```

### ⚙️ Implicit :
If a compiler is converting, then it is known as Implicit

### 💻 Eg :
```java
int a = 10;
float b = a;
System.out.println(a);     // 10
System.out.println(b);   // 10.0  -> implicit
```

---

## 📉 Narrowing :
Converting larger primitive datatype into small primitive datatype is known as Narrowing

### ✍️ Explicit :
If a programmer is converting, then it is known as Explicit.

```java
float b = 20;
int a = (int) b; // Explicit typecasting
(Target value) Reference variable.
```

---
