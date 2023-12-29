---
title: "Java Script For Non-Techies"
datePublished: Fri Dec 29 2023 11:57:15 GMT+0000 (Coordinated Universal Time)
cuid: clqqkwx81000208la4uwmb1cz
slug: java-script-for-non-techies
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1703850086752/db5e7752-cd52-4588-99e2-913c79794675.jpeg

---

# So what is Java Script?

JavaScript is a programming language that can make websites do cool things. It's like a special kind of magic that can make websites come alive!  
When you visit a website, you might see buttons that you can click, forms that you can fill out, and pictures that you can hover over to see a bigger version. All of these things are possible because of JavaScript.

The way it works is that a website sends a special set of instructions called "code" to your computer. Your computer follows those instructions, and that's how you see the website doing all sorts of neat things.  

One cool thing about JavaScript is that it can make websites interact with you. For example, if you type something into a box on a website and press enter, the website can do something with what you typed! It's like the website is listening to you and responding to what you say.

## Let's dive right in:

Let's talk about what coding means. Coding is simply writing instructions that a computer can understand. Just like we write sentences to communicate with each other, we write code to communicate with computers. And just like sentences have grammar and punctuation, code has its own set of rules and structures that we need to follow.  
Now, let's take a look at some basic JavaScript code. Don't worry if it looks confusing at first – we'll break it down together.

```javascript
console.log('Hello, world!');
```

This line of code tells the computer to print the message "Hello, world!" in the console. The console is like a special window where the computer talks back to us.

So, what does this code mean?  
  
Let's break it down step by step:  

`console` This is a special word that tells the computer we want to use the console.  
`log` This is another special word that tells the computer we want to print something in the console.  
`'Hello, world!'` This is the message we want to print. That's it! When we run this code, the computer will print "Hello, world!" in the console.

# Variables

## Let's Explore Variables

In JavaScript, variables are used to store values. They have a name and can hold different values at different times. Kinda like a storage space for info.  
In this guide, we'll explore how to declare and use variables in JavaScript.  

## Declaring Variables

To declare a variable in JavaScript, you use the var, let, or const keyword, followed by the variable name, and an optional initial value.  
  
Here's an example:

```javascript
var myVariable = 'I am a variable!';
```

In the above example, we've declared a variable named myVariable and assigned it an initial value of 'I am a variable!'

## Using Variables

Once you've declared a variable, you can use it in your code.  
  
For example:

```javascript
console.log(myVariable); 
//Output: I am a variable!
```

## Changing Values

You can change the value of a variable at any time.  
  
For example:

```javascript
myVariable = 'I am a changed variable!';
 console.log(myVariable);
 // Output: I am a changed variable!
```

# Syntax

## What even Is syntax?

Syntax refers to the rules that govern how words and symbols are arranged to form valid sentences or statements in a language.  
In programming languages like JavaScript, syntax is critical because it ensures that the code is written correctly and can be understood by humans and computers alike.If the syntax is incorrect the output would result in an error.

## Examples of syntax.

## Indentation :

Use indentation (spaces or tabs) to make your code more readable. JavaScript doesn't care about indentation, but it helps humans understand the structure of your code.

## Curly braces {}

These are used to define blocks of code. Anything inside curly braces is executed together.  
  
For example:

```javascript
{ console.log("Hello!"); 
console.log("I'm an genius!"); } 
```

This code will output both messages to the console.

## Semicolons ;

Semicolons separate statements in JavaScript. Without semicolons, your code won't work properly.  
  
For instance:

```javascript
console.log("Hello!")
console.log("I'm an genius!"); 
```

This code will give you a syntax error because there's no semicolon between the two console logs. To fix it, add semicolons:

```javascript
console.log("Hello!");
 console.log("I'm an genius!"); 
```

## Parentheses ( )

Parentheses group expressions and statements together. You need parentheses when you want to execute something before moving on to the next statement.  
  
For example:

```javascript
 (console.log("Hello!")) ;
 console.log("I'm an genius!"); 
```

The first console log will be executed first, and then the second one will run.

# Data Types

## So what can we store in variables?

There are all kinds of different data which can be stored as a value for the variables that you've declared.  
Here are some examples:  

* Strings - text (Hi, yes...)
    
* Integers - numbers (1, 2...)
    
* Booleans - state (True, False)
    
* Float - not whole number (2.4, 0.5...)
    
* list - set of data (\[3, "4", "hi"\]
    

Let's go through them one by one:

# Strings

Variables can be used to store strings. Strings are like words you use in a sentence.  
String can be empty or can contain one or words of text.  
Strings can be made up of alphabet as well as any number or symbol but they can not be added or subtracted numeralicy.  
  
Here are some examples of strings  
`var string1 = "Hello";   var string2 = "4";   var string3 = "What is the time?";   `

If we try and subtract from our 'string2' variable we will get an error:

```javascript
string4 = string2 - 4; //output: Console error;
```

Now What?

## So when I call myself a programmer?

Now that you know the basics of the Javascript language you can understand how the computer can listen to instructions and follow through them.  
To get started you can practice writing your first bit of code using a js playground which allows you to write code and then it compile it in a way that the computer can understand.  
You can create your own variables and mess around with different data types.  
Of course, there is so much more to know but this was a basic introduction to the vast language known as Java script.  
Once you can properly understand how to read and write large programs written in Javascript you will be able to say that you've mastered the language. In the meantime, you can call yourself a not such a non-techy:)