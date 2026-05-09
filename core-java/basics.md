# 📘 Java Basics

## 1. What is Java
Java is a **high‑level**, **object‑oriented**, and **platform‑independent** programming language.  
It follows the principle **WORA (Write Once, Run Anywhere)** — meaning compiled Java bytecode can run on any system with a JVM.

### Key Characteristics
- Simple  
- Secure  
- Robust  
- Portable  
- Multithreaded  
- High performance (JIT compiler)

---

## 2. JDK vs JRE vs JVM

### JDK (Java Development Kit)
- Contains tools for development: compiler (`javac`), debugger, and JRE  
- Used by developers to **write and compile** Java programs  

### JRE (Java Runtime Environment)
- Contains **JVM + libraries**  
- Used to **run** Java applications  

### JVM (Java Virtual Machine)
- Executes Java bytecode  
- Provides memory management, garbage collection, and security  

### Flow
Java Code (.java)
->
Compiler (javac)
->
Bytecode (.class)
->
JVM executes it


---

## 3. Data Types

### Primitive Types

| Type | Size | Example |
|------|------|----------|
| byte | 1 byte | 10 |
| short | 2 bytes | 100 |
| int | 4 bytes | 1000 |
| long | 8 bytes | 10000L |
| float | 4 bytes | 10.5f |
| double | 8 bytes | 20.99 |
| char | 2 bytes | 'A' |
| boolean | 1 bit | true/false |

### Non‑Primitive Types
- String  
- Arrays  
- Classes  
- Interfaces  

### Wrapper Classes
- Integer  
- Double  
- Boolean  
- Character  
- Long  
- Float

## 4. Variables
Variables are used to store data values in Java.

### Types of Variables
- Local Variables  
- Instance Variables  
- Static Variables  

### Example
class Demo {
    static int count = 0;     // static variable
    int age = 25;             // instance variable

    void show() {
        int x = 10;           // local variable
    }
}

---

## 5. Operators

### Types of Operators
- Arithmetic Operators: +, -, *, /, %
- Relational Operators: ==, !=, >, <, >=, <=
- Logical Operators: &&, ||, !
- Bitwise Operators: &, |, ^, ~, <<, >>
- Assignment Operators: =, +=, -=, *=, /=
- Ternary Operator: condition ? value1 : value2

---

## 6. Control Flow Statements

### Conditional Statements
- if  
- if-else  
- else-if  
- switch  

### Looping Statements
- for  
- while  
- do-while  
- enhanced for loop  

### Jump Statements
- break  
- continue  

---

## 7. Strings
Strings in Java are immutable.

### Important Concepts
- String Pool  
- StringBuilder (mutable, not thread-safe)  
- StringBuffer (mutable, thread-safe)  

### Common Methods
- length()  
- substring()  
- charAt()  
- equals()  
- contains()  

---

## 8. Arrays
Arrays store multiple values of the same type.

### Example
int[] arr = {1, 2, 3};
int[][] matrix = {{1, 2}, {3, 4}};

---

## 9. Methods
Methods define the behavior of a class.

### Concepts
- Method Declaration  
- Parameters  
- Return Types  
- Method Overloading  

---

## 10. OOP Basics

### Core Concepts
- Class  
- Object  
- Constructor  
- this keyword  
- super keyword  

### Four Pillars of OOP
- Encapsulation  
- Inheritance  
- Polymorphism  
- Abstraction  

---

## 11. Access Modifiers

Modifier | Scope
-------- | ------
public | Accessible everywhere
private | Accessible within the same class
protected | Same package + subclasses
default | Same package only

---

## 12. Packages and Imports

### Example
package myapp;
import java.util.Scanner;

---

## 13. Exception Handling

### Keywords
- try  
- catch  
- finally  
- throw  
- throws  

### Example
try {
    int a = 10 / 0;
} catch (Exception e) {
    System.out.println(e);
} finally {
    System.out.println("Always runs");
}

---

## 14. Collections Framework (Introduction)

### Core Interfaces
- List  
- Set  
- Map  

### Common Implementations
- ArrayList  
- HashSet  
- HashMap  

---

## 15. Memory Areas in Java
- Stack: stores method calls and local variables  
- Heap: stores objects  
- Method Area: stores class metadata and static variables  

---

## 16. Garbage Collection
Java automatically removes unused objects from memory.

