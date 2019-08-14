# Lesson Number 2.2 Strings, Lists

# Lesson Outline #

Python Programming an Introduction to Computer Science by John Zelle. Third Edition

Chapter 5.1-5.3

## Intro ##

In the last lesson we learned about numbers. How to manipulate them and the different data types that we can use them in. In this lesson we will talk about text. We will learn how to manipulate text by combining, editing, and changing in every imaginable way.

## Learning Outcomes ##

- Understand what is a String is and how it works
- Be able to concatenation strings
- Be able to format a string 
- Be able to process textual information

## Vocabulary ##

- String
- Indexing
- Sequences
- Concatenation
- Repetition
- Slicing
- Lists

## Additional Resources ##

- https://app.pluralsight.com/player?course=python-fundamentals&author=austin-bingham&name=python-fundamentals-m02-strings&clip=0&mode=live
- https://app.pluralsight.com/player?course=python-fundamentals&author=robert-smallshire&name=python-fundamentals-m05-collections&clip=0&mode=live
- https://www.youtube.com/watch?v=tw7ror9x32s&list=PLBZBJbE_rGRWeh5mIBhD-hhDwSEDxogDg&index=4

# Lesson #

Read pages 129-150

From now on in this course we will refer to text as Strings. A *String* is the data type we use to represent text. When you think about your everyday computer use, you are likely using strings all over the place from word processing to surfing the web. We have already touched on strings a tad in the first lessons. As a reminder you can always create a new string by using the “” with the text inside.

*Indexing* You can call an index on a string to get the character at that Index. Passing in a negative number will go from back end of the string to the beginning. Alternatively you can pass in two numbers to get the range of characters in the string.

*Lists* Perhaps the most important part of this lesson is in 5.3. A list provides a way for us to store all of our data types in what variable. You can create a list that contains a string and a number. In the example below we review how to create a list and how to access data inside of the list.

```python 
daysOfTheWeek = ["Sunday","Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"]
numberInput = int(input("Enter a number for the day of the week: "))
print("The day of the week you selected is", daysOfTheWeek[numberInput - 1])
```
To review the code above. On the first line we create a list with every day of the week contained as strings. 
The second line of code we ask the user to input a number for which day of the week they want.
On the last line of code we print out the day of the week that was selected. Note that we can access items in an array by using square brackets ([]) then putting what index you want inside the brackets ([1]). 

In Python there are built in functions for data types. I want to cover one specifically for lists. *Append* when you want to add another item onto your list you can use the append function. Using the code example above we could append a fake day of the week by writing daysOfTheWeek.append("MTECHDAY"). By doing this our list when then look like ["Sunday","Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "MTECHDAY"]. You'll get some practice using lists and the append function in the assignment for today.

# Assignment #

Your assignment is to do the worksheet found in Google Collaborative. Here is the link. Create a copy of it and answer all of the questions. https://colab.research.google.com/drive/1GJav4tyz2xjzpDbMvwchmiihrzOYgHHn

