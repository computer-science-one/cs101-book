# Why Ruby?

Ruby is an attractive language choice for both beginning and expert programmers. Some of the features which make it a good (introductory) language are:

##### Non-significant whitespace

Some programming languages require a precise amount of whitespace at the beginning of a line. This is a rather unforgiving environment for beginning programmers. Ruby does not suffer from the ailment that is significant whitespace.

##### No semicolons

Some popular programming languages require the termination of lines of code with a semicolon (`;`). This is a tough habit to learn. Ruby does not require semicolons to terminate statements. However, the Ruby interpreter does _tolerate_ semicolons. If you're coming from another language and can't drop the semicolon habit, Ruby won't complain about it.

##### ~~No~~ Few surprises

Ruby is a _consistent_ language. That is to say, it does what you expect (most of the time!). By knowing some parts of the language, you can infer that other parts will work similarly. It is a rewarding experience: writing a new line of code for the first time and having it function correctly.

Other general-purpose languages have odd quirks and hurdles. These inconsistencies can trip up even the most experienced programmers!

##### Write less, do more

Ruby empowers you to do a lot with just a little bit of source code. For example, let's take a look at some introductory-level "Hello world" programs. A "Hello world" program is a simple program which just displays the text, "Hello world" to the screen.

The first program, in Java:

```java
public class HelloWorld {
    public static void main(String[] args) {
        // Prints "Hello, World" to the terminal window.
        System.out.println("Hello, world!");
    }
}
```

This is an example intended for first-time programmers? Yikes! There's an awful lot of material to explain here. We've got visibility, classes, types, arrays, methods, method calls, parameters, string literals... This is a bit overwhelming, even if you dismiss away *most* of these concepts as "don't worry about that little guy, it's magic for now".

Now, let's take a look at the same program in Ruby:

```ruby
puts "Hello, world!"
```

This is much more manageable. Method calls and string literals.