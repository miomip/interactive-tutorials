Variables and Types
-------
In Kotlin there are something called variables, just like in math. <br>
To explain shortly what variables are. They're placeholders for another value, just like x is in math.  

Under here is the most common variables used. <br>
There are more and you can create your own, but these are what's most common.

- `Int` Integers or ints for short are whole numbers without any decimals.
- `Float` Floats are numbers with decimals. The name Float is from how it works, Floating point arithmetic.
- `Double` Doubles are numbers with decimals. The name comes from it needing 8 bytes of ram instead of integers 4 bytes.
- `Char` Characters or chars for short are just single characters/letters.
- `String` Strings are text, the way it work is with an array(list) of chars. The name is from the frase "a string of characters".
- `Boolean` Booleans are either `true` or `false`. The name Boolean comes from the inventor of boolean logic, George Boole.p

In Kotlin there are also two different variables, val and var. <br>
A val is a constant, which means it can't be changed later. A var is a mutable value that can be changed.

Kotlin is something called a dynamically typed language. <br>
Which means it sort of just figures out what the variable is supposed to be.

We are going to show both ways of defining a variable. <br> 
One where we tell it what it is, and one where it figures it out.


### Numbers
To create a variable with it's value as a number you do this:
```kt
  // Integers (// are comments)
  val intVal: Int = 5
  var intVar: Int = 10

  // Doubles
  val doubleVal: Double = 1.0
  var doubleVar: Double = 2.0
```
You can also write it like this:
```kt
  // Integers
  val intVal = 5
  var intVar = 10

  // Doubles
  val doubleVal = 1.0
  val doubleVar = 2.0
```
Floats have two different ways of writing too. <br>
They need the surfix -f, but they can be written both 1.0f and 1f.
```kt
  // First way
  val floatVal = 4f
  var floatVar = 2f

  // Second way
  val floatVal = 4.0f
  var floatVar = 2.0f
```

### Characters and Strings




