# 💻 Write and Execute Java Program

---

## ✍️ Writing Program

To write program in source file we need text editor. The text editor we commonly use are  

- 📝 Notepad  
- 📝 Editplus  

---

## 🖥️ Console

We need console for writing command. Example is command prompt.  

---

## ⚙️ Compilation & Execution

For compiling we have to provide one command and for execution we have to provide one more command.  

### 📌 Commands for compiling and executing  

- 🔧 Command for compiling: javac sourcefilename.java  
- ▶️ Command for executing: java classfilename  

---

## 📌 Example

```java
class Book 
{ 
} 
```

For compiling the command is javac Book.java.  

Since the syntax is correct we will get class file as an output. But when we pass command for executing we will get run time error as “main method not found”. So this is an example for logical mistake.  

---

## ✅ Correct Code

```java
class Book 
{ 
public static void main(String[] args) 
{ 
} 
} 
```

Now if we compile and execute we will get an empty console because we didn’t give anything for printing.
