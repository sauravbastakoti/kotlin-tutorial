# Kotlin Tutorial for Beginners

Welcome to the **Kotlin Tutorial for Beginners**! This guide will help you get started with Kotlin programming from scratch.

## Table of Contents
1. [Introduction to Kotlin](#introduction-to-kotlin)
2. [Installing Kotlin](#installing-kotlin)
3. [Hello World in Kotlin](#hello-world-in-kotlin)
4. [Basic Syntax](#basic-syntax)
5. [Variables and Data Types](#variables-and-data-types)
6. [Control Flow](#control-flow)
7. [Functions](#functions)
8. [Classes and Objects](#classes-and-objects)
9. [Collections](#collections)
10. [Basic Exercises](#basic-exercises)

---

## Introduction to Kotlin
Kotlin is a modern, statically typed programming language developed by **JetBrains**. It is fully interoperable with Java and widely used for Android development, web development, and server-side applications.

### Why Kotlin?
- Concise and expressive syntax
- Interoperability with Java
- Null safety feature
- Functional programming support

---

## Installing Kotlin
You can run Kotlin code in multiple ways:

### 1. Online Kotlin Playground
Visit [Kotlin Playground](https://play.kotlinlang.org/) to run Kotlin programs directly in your browser.

### 2. Install Kotlin on Your Machine
#### a) Using IntelliJ IDEA
- Download and install **IntelliJ IDEA** from [JetBrains](https://www.jetbrains.com/idea/)
- Create a new **Kotlin Project**
- Start coding!

#### b) Using Kotlin Command Line Compiler
- Install Java JDK (if not installed already)
- Install Kotlin using SDKMAN:
  ```sh
  sdk install kotlin
  ```
- Verify installation:
  ```sh
  kotlin -version
  ```

---

## Hello World in Kotlin
Let's start with the classic **Hello World** program in Kotlin:

```kotlin
fun main() {
    println("Hello, Kotlin!")
}
```

### Explanation:
- `fun main()` is the entry point of the program.
- `println()` prints output to the console.

---

## Basic Syntax
### 1. Comments
```kotlin
// This is a single-line comment
/* This is a multi-line comment */
```

### 2. Variables
```kotlin
val name = "Kotlin"  // Immutable variable
var age = 25         // Mutable variable
```

### 3. String Interpolation
```kotlin
val name = "Alice"
println("Hello, my name is $name")
```

---

## Variables and Data Types
Kotlin has two types of variables:
- `val` (Immutable)
- `var` (Mutable)

### Example:
```kotlin
val language = "Kotlin"  // Immutable
var age = 21             // Mutable
age = 22  // Allowed
```

### Data Types in Kotlin
```kotlin
val myInt: Int = 10
val myDouble: Double = 10.5
val myChar: Char = 'A'
val myBoolean: Boolean = true
```

---

## Control Flow
### 1. If-Else Statement
```kotlin
val age = 18
if (age >= 18) {
    println("You are an adult")
} else {
    println("You are a minor")
}
```

### 2. When (Switch Case Alternative)
```kotlin
val number = 2
when (number) {
    1 -> println("One")
    2 -> println("Two")
    else -> println("Unknown number")
}
```

---

## Functions
```kotlin
fun add(a: Int, b: Int): Int {
    return a + b
}

fun main() {
    val sum = add(5, 10)
    println("Sum: $sum")
}
```

---

## Classes and Objects
```kotlin
class Person(val name: String, var age: Int) {
    fun introduce() {
        println("Hi, I'm $name and I'm $age years old.")
    }
}

fun main() {
    val person = Person("Alice", 25)
    person.introduce()
}
```

---

## Collections
### 1. Lists
```kotlin
val numbers = listOf(1, 2, 3, 4, 5)  // Immutable list
val mutableNumbers = mutableListOf(1, 2, 3)
mutableNumbers.add(4)
```

### 2. Maps
```kotlin
val countryCodes = mapOf("US" to "United States", "NP" to "Nepal")
println(countryCodes["NP"])  // Output: Nepal
```

---

## Basic Exercises
1. **Write a program to check if a number is even or odd.**
2. **Write a function to find the factorial of a number.**
3. **Create a class `Car` with properties like `brand` and `model`, and a function to display details.**
4. **Write a program to reverse a string.**

---

## Contributing
Feel free to fork this repository and contribute by adding more examples and explanations!

## License
This tutorial is open-source and free to use under the **MIT License**.
