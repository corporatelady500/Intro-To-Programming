# Lesson Number 1

Your first day of Python! Have an open mind and let's get started.

# Lesson Outline #

Python Programming an Introduction to Computer Science by John Zelle. Third Edition

Chapter 2.1-2.5 Pages 27-41

## Intro ##

Welcome to Intro To Programming! We are going to jump right in to writing some code on the first day. Prepare yourself to learn quickly and be excited about the small things that you are able to accomplish. As we go through the lessons make sure to take your time and understand what is going on. There are additional resources in each lesson including this one. If you don't understand something, please do your best to give it more time. Nailing these concepts will aide you in completing the first project.

## Learning Outcomes ##

- Understand the Development Process and be able to think through what steps are needed to bring a project from nothing to something
- Understand simple expressions and variables
- Be able to create, modify, and process simple expressions

## Vocabulary ##

- Python
- Names
- Expressions
- Programming
- Software Development Process
- Variable
- IDE

## Additional Resources ##

- This video goes over the Software Development Process more in depth. Note that they have 7 steps instead of 6, but it covers the same thing. https://www.youtube.com/watch?v=i-QyW8D3ei0

- For a recap on learning about math and variable check out this video. He walks you through doing some simple math expressions. https://www.youtube.com/watch?v=XM0CtrJYM2A

- Need help setting up your work environment to start writing Python check out some of these options. For Google Colab https://www.youtube.com/watch?v=inN8seMm7UI, for using a local IDE such as Pycharm https://www.youtube.com/watch?v=BPC-bGdBSM8&list=PLQ176FUIyIUZ1mwB-uImQE-gmkwzjNLjP

# Lesson #

## Software Development Process ##

Before you write our first lines of code let's understand the process that should happen before you sit down to start working on a project. Open up the book flip to page 27 and read section 2.1. 

Let's recap the six steps that the book has in the development process.
1. Analyze the Problem
2. Determine Specifications
3. Create a Design
4. Implement the Design
5. Test / Debug the Program
6. Maintain the Program

We are going to work through a project idea together. Start to think about a project that you will want to do, because at the end of this lesson you will be asked to think through the Software Development Process on your own for your own project.

Our project is a Pizza Delivery Service for the MTech culinary program. Keep in mind this project is hypothetical, but try to think of it as a real life project.

1. Analyze the Problem

The Culinary Department makes great pizza but has no way for companies or people to order the pizza without coming into the cafeteria in person. They have the students willing to make the pizza and deliver it. 

2. Determine Specifications

To solve the problem we will create a mobile app that companies or people can order pizza, as well as have an interface for Mtech to be able to respond to orders. We will have to be able to login as a customer or as MTech. As a customer we need to be able to create an order, pay for the order, see where the delivery man is with up to date progress on the pizza, and give a review! As Mtech we need to be able to receive orders, receive payment, respond to reviews, give updates on the progress of the pizza, and manage their menu. Phew good thing we are not actually going to build this app it sounds like it will be a lot of work!

3. Create a Design

Time to start thinking about what this app is going to look like! How will they login, will they use Facebook, Google, Apple, etc... In this step we would draw out each screen and determine how a user would navigate through the application. What algorithms or services may we need to make each aspect of the application doable. Since we are just getting started I want you to think about how the application will look. Don't worry right now about what algorithms you will use to accomplish the task. 

4. Implement the Design

This step is where you start to write the code. This is the longest step in the process. Every little aspect of the application needs code behind it. As programmers we don't touch step three very often, in most circumstances there will be a designer who will think through that step for you. Our job is to create the application as close to the design as possible. Let's just think about a login page as an example. What colors will be used? How will the user enter their information? How will we manage the keyboard? If we are using a third party service, how do we interact with Facebook, Google, or Apple? If the user name is already taken, how will we know? How will we notify the user that their username is taken? There is a lot that goes into every aspect of a program it's your job to think through all of it. Programmers always say that they last 10% of the project takes just as long as the first 90%

5. Test / Debug the Program

Okay so we have written our code and our program is perfect and ready to go right? No, we aren't perfect there will always be errors. Never in your life will you write a perfect code base and that's okay, it's expected! It is critical to test our program. Can you break it? What if I order 1,000 pizzas how will the system manage that? Should I be allowed to do that? 

6. Maintain the Program

New technologies are always coming out, there is always something new that you can add to the program. MTech may decide that their pizza delivery service is booming and wants to expand it to their Turkey Bacon Avocados sandwiches (Mmm delicious 10/10 would recommend). Perhaps Facebook, Google, or Apple changed the way their login works and we need to update our code to match the new way to do. While a code base may be great to start overtime there will be things that need to change. Updates are crucial to the success of a program. No program is done when it originally hits production, there are always changes that have to happen for the success of the program.

That's a quick look at what the Development Process may look like to build a Pizza Delivery App for the MTech Culinary department. This whole process may takes years to follow through and do effectively. A reminder to start thinking of what kind of project you want to think through after this lesson in the assignment.

## Expressions ##

Before we get started please read pages 31-41 in the book.

Now that you have a basic understanding of expressions we will touch on the most important parts then do a couple of examples together to cement your understanding of expressions and assigning values to variables.

*Data Types* In this lesson we are going to cover two different data types numbers and strings. We will cover many other data types but to get started we will just do these two. *Numbers* Numbers encompass all numbers that you can think of whether that be whole numbers like 8 or decimals like 1.2. *Strings* Strings are the way we represent text in code. This whole lesson is just one big string! Strings can include numbers as well, in python a string is anything that is surrounding be quotes. We will go over some examples a little further down.

*Variables* This is the bread and butter of any programming language. Variables are how we store data to be used in our program. Thinking back to our pizza delivery app we would create variables for every type of data that we need to gather. With the login screen we would need to have a variable for the username and password that the user enters. Those variables would be of the data type string. All variables have a data type, for today we will use examples of numbers and string. When we name variables we should do our best to name them for what kind of data they will contain. If you were to capture a string for your favorite color you might want to name it favoriteColor. Note that in variable names a common convention is to capitalize the first letter of every word after the first. This makes it easy to read the whole variable name.

*Expressions* We can use our different variables to create expressions. Maybe we want to combine two different string variables, or we may want to do some simple math with our variables. Let's check out some examples.

*Examples*

```python
firstName = "Elon"
lastName = "Musk"
fullName = firstName + lastName
print(fullName)
```
Here we created three different variables firstName, lastName, and fullName. We assign the variable a value by using the = symbol. After the =  we give the value. Since names are strings we wrap the value in the quotes. With the fullName variable we used something called string concatenation. It takes our first two variables and puts them together. The result would be "ElonMusk". Lastly we print our variable to the console which allows us to check to make sure our code is running as expected. 

```python
firstNumber = 8
secondNumber = 2
print(firstNumber * secondNumber)
```

Two variables have been created each holding a number. Inside the print statement some simple math is done. The console will print 16.

```python
firstNumber = 8
secondNumber = 2
thirdNumber = firstNumber + secondNumber
```

Using the two variable from earlier you can create another variable from those two numbers to create something new.

```python
firstNumber = 8
firstNumber = firstNumber + 1
```

With one variable you can use it again to update its value. After this code is completed firstNumber would be 9.

```python
age = input("Enter your age: ")
```

Using the keyword input you are able to gather information from the user. After running this code you will be prompted to type in a response. After entering a response that data is stored in the variable age.

## Getting you started in an IDE ##

Now that you've seen some code let's get you going with writing your own code. When we write code we do so in an IDE or Integrated Development Environment. The IDE will be helpful and show you errors in your code and help with color coding your code as well. In this class we will cover two different IDE's you are welcome to use whichever one you find easier to use.

*Google Collaborative* is a great way to be able to code from anywhere and have it stored online for you. You access Google Collaborative from your browser. All of your work is saved in your Google drive. The link to get started is https://colab.research.google.com/. Occasionally the assignments in this class will be a worksheet from Google Collaborative so it will be good to be familiar with it. 

*PyCharm* is the standard IDE for python developers. It is currently installed on your machine. All you need to do it open it up and start a new project! Note that your PyCharm projects won't be saved online and you will only have access to them while you are on the current machine you are using.

If you want some help setting up your IDE ask the teacher or check out these videos or Google Colab https://www.youtube.com/watch?v=inN8seMm7UI, for using a local IDE such as Pycharm https://www.youtube.com/watch?v=BPC-bGdBSM8&list=PLQ176FUIyIUZ1mwB-uImQE-gmkwzjNLjP


# Assignment #

The first part of your Assignment is to create your own development process for a project of your own. Think of a project it can be something that already exists or something that you want to create one day. Create a text document that walks through each step. For reference you can see the example in this lesson or read section 2.2 on page 28 in the book.

The second part of your assignment is to do the worksheet found in Google Collaborative. Here is the link. Create a copy of it and answer all of the questions. https://colab.research.google.com/drive/1HSUjokXr73p48mfPT8ZMEwbf2sz2MWBj

Turn in both documents on Canvas.

## Recap ##

Congratulations you finished your first lesson in coding! You've learned a little bit about the software development process. You should be able to think about each step and what needs to be done on each step. You wrote your first lines of code! You should be able to create a simple variable. As well you should be able to receive input from the keyboard and give output as well! Well done! 