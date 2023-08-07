# J--

[![Downloads](https://img.shields.io/github/downloads/JDashDash/J--/total?style=for-the-badge)](https://github.com/JDashDash/J--)
[![Code size](https://img.shields.io/github/languages/code-size/JDashDash/J--?style=for-the-badge)](https://github.com/JDashDash/J--)
[![Last Release](https://img.shields.io/github/release/JDashDash/J--?style=for-the-badge)](https://github.com/JDashDash/J--)
![J-- Logo](https://media.discordapp.net/attachments/781983259210547280/1138129595116294224/J--.png?width=402&height=402)


## Description

J-- (J Dash Dash) is an interpreted, non-object-oriented programming language inspired by the C++ language and the very famous Java.

Java is one of the most used languages in the world of developers, however it is the source of many problems.

The language with this name following the inspiration of Java and if we find "Dash Dash" it is due to the inspiration of C++ and its use for the design of J--.

The language will use files with the extension *.jdd*.

## Example
```
print("Hello World V1 \n");
println("Hi");

int a = 5;
double b = 52.3;
string a = "cc";
boolean c = true;

private void myFunc() {
    print("Only this file can call this one");
}

public void myFunc() {
    print("Every files .jdd can call me !");
}

protected void myFunc() [file.jdd] {
    print("files.jdd can call me");
}

// Comment, protected function != protected function in a class

/*
comment
here
*/
```

## Modules

Modules are "utilities" that users can add using the "import" statement (see the language documentation):

### Example

```
import String;

println("hi".concat("cc"));
println("hi".getIndexFromChar("h"));
println("hi".getCharFromIndex(0));
println("hi".getCharFromIndex(1));
println("hi".getCharFromIndex(2)); // Return void because it does not exist
println("hi".equals("hi"));
println("hi".equals("Hi"));
println("hi".equalsIgnoreCase("hi"));
println("hi".equalsIgnoreCase("hI"));
println("hi".equalsIgnoreCase("HI"));
println("".isEmpty());
println("c".isEmpty());
println("cc".isEmpty());
println("CC".toLowerCase());
println("CC".toUpperCase());
println("cc".toUpperCase());
println("ccaa bb".replace("a", "b"));
println("ccaa bb".replace("b", "a"));
```

```
import Integer;

int a = Integer.sum(10, 5);
println(a);
a = Integer.mul(a, 5);
println(a);
a = Integer.div(a, 2);
println(a);
a = Integer.sub(a, 3);
println(a);
a = Integer.fromBoolean(true);
println(a);
a = Integer.fromBoolean(false);
println(a);
a = Integer.abs(50);
println(a);
```

## Links

[Source Code](https://github.com/JDashDash/J--)

[Modules](https://github.com/JDashDash/Modules)

[Discord Server](https://discord.gg/PsC9gjm65U)

[Website]()

## JetBrains

JetBrains gives access to tools in the computer world and gives access to developers proposing interesting projects being opensource.

[Website JetBrains](https://www.jetbrains.com/)

[CLion](https://www.jetbrains.com/clion/)
