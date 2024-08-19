Commandline game
------

Just to start. I'm not going to give you the completed code. <br> 
You're going to make wordle.
I'll say what you need and give you some bits of code that is confusing or is just optional(colored text, etc.)

### What you're going to need
 - Main loop.
 - A list of words.
 - Function for guessing a word. (recursion might come in hand for invalid guesses)
 - Function to check if the word guessed is right. ( .lowercase and .lowercaseChar should be usefull and .count might come in handy)
 - Function/variable to get a random word from the list of words. (nextInt should be usefull for this)
 - A check for if the word is guessed. (Can be done using an if statement)
 - Print out the placement of letters guessed right. And _ for which isn't guessed yet.
 - Count of tries left.



### Optional
 - Colored text.
 - Function to import text from a file

For colored text you can use Ansi codes like these
```kt
  val red = "\u001b[31m"
  val green = "\u001b[32m"
  val bold = "\u001b[1m"

  val resetColor = "\u001b[0m"
```
To use them you can just insert them into print like this
```kt
  println(red + "Hello" + resetColor)
```
You have to reset the color because otherwise it will apply for everything else, even after that expression.

The file import function is something like this(example works)
```kt
 fun getsWordsFromFile(filePath: String, list: MutableList<String>) = File(filePath).forEachLine { list.add(it) } 
```
