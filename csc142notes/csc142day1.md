# CSC 142 Day 1

An interpreted language translates line by line from the language into machine language and runs it line by line.
Because of this you need the correct enviornment to run whatever language. Browsers have JavaScript translators built in.
Interpreted languages are also generally a little bit slower.
File type examples: `.py`

A Compiled language takes in the whole program and turns it all into machine language.
Because of this is, no enviornment is needed. They spit out `exe`s and `dll`s.
Programs from compiled languages are generally a lot faster.
File type examples: `.c` would be source code, `.exe and .dll` would be the compiled ready to run code.

Java is hybrid language. It has aspects of both. Dot Net is the other hybrid.
Java will take in the entire program and then produce byte code.
Byte code is machine language for a virtual machine called `JVM`. No machine actually runs JVM. Byte code is just very close to all machine languages but not fully done.
The `Java Runtime` (interpreter) will finish translating the byte code to the actual language of that specific machine.
File types: `.java` is the source code, `.class` is the byte code.

Java gets machine independence by that most of the way translation. Instead of needing a full Java enviornment, like someone would with python, they just need that small Java Runtime component to finish the translation. Compiled is very fast and efficient but is machine dependant.


## Classes

Classes are named with PascalCasing. That is they always start with an upper case letter.

Function names, parameters, and variables use camelCase. For global constants you name IN_ALL_CAPS.

## Methods

Methods are functions that are attached to something.

In Java ALL functions are methods.


When making a class, for now, always make a main method that is:

```
public static void main(String[] args) {
        
        
}
```

In Java, and a lot of other languages, you HAVE to use `" "` to wrap a string. You cannot use apostrophes like in Python.
You end every code statement with a semicolon.

Everything is declared in Java. So above the void just says that method is not returning anything. 

## Primitives

Integral: byte, short, int, and long. These explain how many bits. From left to right it is 8, 16, 32, and 64.
Floating: float, double. (32 bits, 64 bits)
Other: char, boolean.

Char can hold one character at a time.