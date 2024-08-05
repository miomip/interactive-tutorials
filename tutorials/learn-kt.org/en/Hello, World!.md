### Introduction
Kotlin is an object oriented language (OOP). Just like Java is! <br>
It simply means you can have your code seperated in object called "Kotlin classes". <br>
Classes are not like in Java, forced upon you. So we will take that later.

### Our first program!
Let's take a look at a program that writes Hello, World! And go over what the different things are.

```kt
  fun main() { 
      println("Hello, World!");
  }
```

First thing you can see is a function called main. <br>
This little one:
```kt
  fun main()
```
Everything inside the curly braces will be ran when running the program.
  - `fun` is telling the pc it's a function.
  - `main` is the name.
  - `()` is where potential arguments will go. Don't worry about it for now.

Now, we have to look at the little guy inside main
```kt
  println("Hello, World!")
```
A bit big. Let's break it down even further.
```kt
  println()
```
There. This is the built in function for prining something to the terminal(Aka, window with a buch of weird white text) <br>
You're probably asking why is it called `println()`? It's because it makes a new line after itself. Therefor nl after print.

Let's look at that inside of `println()`
```kt
  "Hello, World!"
```
As you can see there are double quotation marks on each side of Hello, World!. This is to tell the pc it's a String(text).

### Exercise
Change the code so it prints out "Hello, World!".

### Tutorial Code
```kt
  fun main(){
      println("Hello, Kotlin!")
  }
```
### Expected Output
```
Hello, World
```
### Solution
```kt
  fun main(){
      println("Hello, World!")
  }
```



