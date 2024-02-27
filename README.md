# sp24-lab7
Materials for week 7 lab in CS-370, which includes Ch. 8 "Functions & Closures" adapted from [Software Design by Example](https://third-bit.com/sdxpy/) by Greg Wilson.

_February 27, 2024_

Organization:
* SDX-ch9: The code files for the _SDX Ch. 8_ activity (as downloaded directly from the book website, unmodified) 

## Team Members for Part 1
Terence and Shahrom 

## Team Roles for Part 1
Who will start out as
* DRIVER: Terence 
* NAVIGATOR: Shahrom

You will switch halfway through the _SDX Ch. 9_ activity.

## Part 1 Documentation

Write your answers to the questions below.

* What were the main ideas from SDX chapter 8?
- How to use decorators, mock objects and understanding protocols. 
* What questions did you have about the material in the chapters? What did you find confusing?
- We found pretty much everyhting confusing becuase they were all new concepts. The examples made little sense after multiple readings and we had a hard time understanding and seeing the use of this concepts in large scale projects. 


Fill in the following table with your definitions and examples for the main concepts of this chapter --- mock objects, context managers, decorators, iterators.

| Concept | Brief Definition | When to use (generally) | Potential uses in audio archive project |
| --- | --- | --- | --- |
| **mock objects** | Mock obects are place holders that simulate the behaviour of real objects.| They are genereally used in unit testing to isolate code and run tests on individual code blocks. | We will most likely use mock objects in the testing phase of the audio archive.|
| **context managers** | Context managers are objects that make sure resources are properly initialized before execution of a code block and properly cleanup aterwards.  | The general use cases are; file handling, testing and database connections.| If we implement audio editing we will need to use context managers to deal with the opening and closing up of the files.|
| **decorators** | They are functions that wrap around other functions.| They are generally used for user authentication, loggging and caching| If we want to implement some level of user authorization before gaining access to the audio archive.|
| **iterators** |They are objects that are used to iterate over collections of data |General use case: iterate | Iterate over the sounds in the audio archive |


Write a short summary of what you did (which exercises) below.
