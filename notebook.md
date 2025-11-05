# My coding notebook

## Table of Contents
[Flutter Definitions](#flutter_definitions)
- [what is flutter?](#what-is-flutter)
- [Key terms and definitions](#key-terms-and-deifinitions)
- [layout and design widgets](layout-and-disign-widgets)
- [definitions with structures](#flutter-definitions)
- [Code Definitions](#code-definitions)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

## Flutter Notes

### What is Flutter?
- Definition:
- Why is it useful?

---

### Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |                                                  |                                           |
| MaterialApp      |                                                  |                                           |
| Scaffold         |                                                  |                                           |
| StatelessWidget  |                                                  |                                           |
| StatefulWidget   |                                                  |                                           |
| Navigator        |                                                  |                                           |
| AppBar           |                                                  |                                           |
| Column           |                                                  |                                           |
| Row              |                                                  |                                           |
| Container        |                                                  |                                           |
| Text             |                                                  |                                           |
| Image.network    |                                                  |                                           |

| Padding    |                    |                     |

| Center |                        |                     |

---

### Layout and Design Widgets
- How do you center a widget?
- How do you align something to the left or right?
- What widget adds space around content?


 [Code Definitions](#code_definitions)

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |

|------|------------|--------------------------|-------------------|-------------|

|      | A named container used to store a value that may change. | `var x = 5;` | student age = 15 |  | main.dart, Spring title: 'TSA Portfolio |

|      | A fixed value that cannot change once set. | `const PI = 3.14;` |  | main.dart, const, MyPortfolioApp((super.Key)); |

|      | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  | main.dart, bool, debugShowCheckedModeBanner, false |

|      | A sequence of characters used to represent words or text. | `"Hello World"` |  |  |

|      | Whole number values. | `int age = 16;` |  |  |

|     | Number values with decimals. | `double age = 16.2;` |  |  |

|      | A value that can be true or false. | `bool isLoggedIn = false;` |  |  |

|      | A collection of values in a specific order. | `List<String> names = [];` |  |  |

|      | A special value that means “nothing.” | `String? name = null;` |  |  |

|      | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  |

|      | The information passed into a function to change how it works. | `greet(String name)` |  |  |

|      | The result a function gives back. | `return total;` |  |  |

|      | Where a variable or function can be used. | (No set syntax — concept-based) |  |  |

|      | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |

|      | A specific version of a class. | `Dog myDog = Dog();` |  |  |

|     | A variable that belongs to a class/object. | `String name;` |  |  |

|     | A function that belongs to a class. | `void bark() {}` |  |  |

|     | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |

|      | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |

|      | Changing how a built-in or inherited function behaves. | `@override` |  |  |

|      | A function that does not return a value. | `void printMessage() {}` |  |  |
|             |  |  |  |  |
|             |  |  |  |  |
| Scanner | Creates a scanner object to take input from user | Scanner in = new Scanner (System. in); ||| 

| import Scanner | Gives access to Scanner class, required at top | import java.util.Scanner; |||

| print line statement | prints the content in the parenthesis, adds line after | System. out.println(" ");

| print statement | prints the content in the parenthesis | System.out.print(" "); | | 

|I input nextLine | reads in a String from the user input.nextLine(); 

| input nextInt | reads in an int from the user linput.nextInt()

;| input nextDouble | reads in a double (decimal) from the user input.nextDouble);/ I input nextBoolean

reads in a boolean (true/false) from the user | input.nextBoolean(); |

| Minimum int | the minimum value an int can hold: -2147483648 | Integer.MIN_VALUE |||

| interger overflow | interger.MAX_VALUE + 1 ==MIN_VALUE, its wraps around ||||

| underground underflow |

| cocatenate | To combine Strings with other with Strings and/or variables | Strings greeting = "hello" + "My name is" + name ". " ; ||
## Flutter Definitions with structures

| Term | Definition and Description | Base Structure | Real Life Example | App Example |

|------|----------------------------|----------------|-------------------|-------------|

| main() | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  | in main.dart, void main() => runApp(MyPortfolioApp()); |

| materialApp | A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |

| scaffold | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  | in showcase.dart,  return Scaffold(
      body: Column(
 mainAxisAlignment: MainAxisAlignment.start,
        children: [ |

| column | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |

| row | A widget that shows things side-by-side. | `Row(...)` |  |  |

| container | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |

| text | A widget to display text on the screen. | `Text('Hello')` |  |  |

| image.network | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |

| elevatedButton | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |

| onPressed | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |

| StatelessWidget | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |

| Navigator | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |

| Navigator.pushNamed | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |

| padding | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |  |

| center | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |

| wrap | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |

| override | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |

| widgetBuild | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |

| build | Required in every widget class to describe what to show. | `build` |  |  |

| buildContext | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |

| super.key | A keyword used to pass a value to the parent widget. | `super.key` |  |  |

| const | A keyword that means the value won't change and is set once. | `const` |  |  |
