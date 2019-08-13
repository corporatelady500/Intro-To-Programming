# Lesson Number 2.1 Numbering

# Lesson Outline #

Python Programming an Introduction to Computer Science by John Zelle. Third Edition

Chapter 3.1-3.4 Pages 57-75

## Intro ##

Today we are going to cover numbers! In Python and other programming languages you create variables with types. Today we will cover all of the types that include numbers. For example, there are decimals, large numbers, small numbers, exponents, square roots, etc... Today we will go over the different number data types and what mathematical processes you can do with the different number data types.

## Learning Outcomes ##

- Understand what is a data type and when you use them
- Understand multiple data types for numbers and be able to use them in mathematical equations
- Understand what the Python Math Library is, be able to implement it in a project, and use it efficiently
- Be able to process mathematical equations 

## Vocabulary ##

- Data Type
- Operator
- Operation
- Type Conversions
- Rounding
- Python Library
- Factorials

## Additional Resources ##

Links to videos and examples that they can go to in order to learn more

# Lesson #

Open the book and read pages 57-71

There are two number data types that we will cover today. *Integers* are whole numbers. That means no decimals just the number. 1,2,3,4,5 all are what we call in python as integers. *Floats* are numbers that have a decimal.  Pi is a great example of a float, 3.14. It's important to recognize the different between an Integer and a Float. When writing code that involves numbers you will want your numbers to match to get the most accurate answers. If you are hard coding a number into your code you can make it a float by just adding .0 to the end. For example, if I wanted to use the number 2, but wanted it as a float and not an integer I would need to type 2.0 instead.

Let's say we do not use the same data types, this will cause rounding issues for us. Open up your preferred way of writing python and experiment to understand how the two data types interact with each other. Multiply and divide an integer to a float and see if you get the right answer. To get a deeper understanding re-read section 3.2 pages 62 in the book. As well you can check out some of the videos in the Additional resources section of this lesson.

The *Math Library* can be a powerful resourse for you to do mathematical equations with ease. In the book it showed you how to do the quadratic formula. Here we will show you how to do the pythogrean theorem using the math library. For more information on the many tools available in the math library make sure to check out the videos in the additional resources of this lesson!

Pythagorean theorem: a^2 + b^2 = c^2 or c = Square Root of a^2 + b^2

```python
import math

a= float(input("Enter coefficient a: "))
b= float(input("Enter coefficient b: "))

answer = math.sqrt(math.pow(a,2) + math.pow(b,2))

print(answer)
```

If you want a more in depth look at numbers and the limitations that there are with numbers in python compared to other langauges keep reading in this chapter pages 71-75.

# Assignment #

Your assignment is to do the worksheet found in Google Collaborative. Here is the link. Create a copy of it and answer all of the questions. https://colab.research.google.com/drive/1GJav4tyz2xjzpDbMvwchmiihrzOYgHHn
