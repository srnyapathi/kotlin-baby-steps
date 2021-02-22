# Quick Intro to Kotlin

Kotlin is a cross-platform statically typed language with type inference. Designed to interoperate with java. 
TLDR;

Kotlin has made the lives of java programmer much simpler. There are no semi colons , long syntaxes and annyoing {} only code that matters the most . 

Simple hello world example in java 

```java
package blah.blah.blah

class HelloWorld {
  public static void main(String[] args){
    System.out.println("Hello World");
  }

}
```
In total we have 6 lines of code with long syntaxes and fancy symobls. just for printing "Hello World!".
If someone looks at it for the first time they should know what is public static void main and static and main which is too much of ceremony and clutter for a programmer.

Jetbrains , had the same problem huge code base and it was getting difficult to maintain. They came up with a language which make work productive and also makes the life of developer easy
The whole and sole purpose of code is to make code look like a well written prose.Its not only that , but  there is more to it . 

Same example in Kotlin
```kotlin
fun main(args:Array<String>){
  println "hello world"
}
```
3 lines and you are done ! 
In the backgroud , it did all the heavy lifting for you
- created a class based on the file name 
- converted println to System.out.println.

Lesser the number of lines of code , lesser the number of bugs and easy to maintain .
This is not just reducing the lines of code but it also has some powerful features.

