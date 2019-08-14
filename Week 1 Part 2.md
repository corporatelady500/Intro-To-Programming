# Lesson Number 1.2 Loops

# Lesson Outline #

Python Programming an Introduction to Computer Science by John Zelle. Third Edition

Chapter 2.6-2.7 Pages 43-49

## Intro ##

Today you'll be learning about loops! Loops are an essential part of any programming language. At time you will have a collection of items and using a loop is a great way to go and manage the items in a collection. There are many types of loops, you will get a chance to see many of them in action today.

## Learning Outcomes ##

- Understand the different type of loops 
- Be able to write your own definite loop to add numbers together

## Vocabulary ##

- Definite Loop
- Counted Loop
- Range
- Conditionals
- Modulo


## Additional Resources ##

- https://www.youtube.com/watch?v=OnDr4J2UXSA
- https://www.youtube.com/watch?v=6iF8Xb7Z3wQ

# Lesson #

## Loops ##

Read Pages 43-47 in the book.

Loops are an essential part of programming. In this lesson we are only focusing on Definite Loops. That means that the loop will be run a set number of times. If we were to loop through every number between 1-20 the code would be run 20 times. In future lessons we will talk about other loops that are run differently.

After this program and Web Development or Mobile Development you will want to start interviewing at companies for a developer job. One of the most common job interview questions is called FizzBuzz we are doing to put a twist on it and solve it together.

The question: Write a program that prints the numbers from 1 to 20. But for multiples of three print “Mountainland” instead of the number and for the multiples of five print “Technical”. For numbers which are multiples of both three and five print “Mountainland Technical College”.

In order to solve the program let's cover two more things that will be new. *Conditionals* A conditional is a statement that can be run in order to only run a piece of code if it meets certain conditions. The condition in this case will be if a number is a multiple of 3 or 5.
Next how will we determine if a number if a multiple of 3 or 5? *Modulo* Here we get to learn about the modulo operator. We can use the number then the modulo operator (%) to find the remainder. 

Now to solve the question. Create a for loop, add conditional statements for if the number is divisible by 3 and 5, add print statements where necessary. The final product will look something like this:
```python
for num in range(1, 21):
    if num % 3 == 0 and num % 5 == 0:
        print('Mountaind Technical College')
    elif num % 3 == 0:
        print('Mountaind')
    elif num % 5 == 0:
        print('College')
    else:
        print(num)
```

Try putting that into your favorite IDE and play around with it. Change numbers, change the order, make the range bigger. Continue to play with the code to understand each piece. 

## Example Program ##

Build out the example program with the book. Pages 47-49

# Assignment #

Turn in the Example Program in 2.7 in whatever IDE you did it in.

The second part of your assignment is to do the worksheet found in Google Collaborative. Here is the link. Create a copy of it and answer all of the questions. https://colab.research.google.com/drive/19-U7NpCYxCgBs99EAp-vAdy6ymLzVdzw

## Recap ##

Congratulations you have completed the first bit of Python Programming! In your project for this week we are gonna dive in and let you work out some programming on your own. If needed look back on the resources in the last two lessons to gain more confidence to move forward. Be sure to complete the example program in this lesson in order to be best prepared for the project! Good luck!
