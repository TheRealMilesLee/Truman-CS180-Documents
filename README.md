# Truman-CS180-Documents
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
<a href="https://996.icu"><img src="https://img.shields.io/badge/link-996.icu-red.svg"></a>
<a href="https://img.shields.io"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg"></a> 
<a href="https://img.shields.io"><img src="https://img.shields.io/badge/C++-Learing-red.svg"></a>
<a href="https://img.shields.io"><img src="https://img.shields.io/badge/Creative-Design%26Build-blue.svg"></a>
<a href="https://img.shields.io"><img src="https://img.shields.io/badge/MileLee-Computer%20Science-brightgreen.svg"></a>

This is the supporting documents and notes for the truman CS180 course

# Index
[Test 1](https://github.com/TheRealMilesLee/Truman-CS180-Documents/blob/master/Test%201.docx) This is the first test of this course, it contains chapter 1 - 3, and for the lab is the lab1 - lab4. The main knowledge points were: data type, variable definition, random function, cin and cout, do basic math in variables with different data types, and write a full program that contains all these above.

[Test 2](https://github.com/TheRealMilesLee/Truman-CS180-Documents/blob/master/Test%202.docx) This is the second test of this course, it contains chapter 4 - 6, and for the lab is the lab5 - lab8. The main knowledge points were: Truth table, abs function and EPSILON method to compare two double values that they are equal or not. Also, in this test contains the validation for the user input and the biggest-smallest comparison algorithm. This test tests your ability to write the Javadoc and identify three different loop structure's difference.

[Test 3](https://github.com/TheRealMilesLee/Truman-CS180-Documents/blob/master/Test%203.docx) This is the third test of this course, it contains chapter 6 - 8, and for the lab is the lab9 - lab12. The main knowledge points were: Bubble sort algorithm, linear search algorithm, array, binary search algorithm, vector, pointer, Javadoc and the prototype of a function, the function call and the graph of how the parameter doing.

[Test 4](https://github.com/TheRealMilesLee/Truman-CS180-Documents/blob/master/Test%204.docx) This is the Mistake collection from test 1

[Test 5](https://github.com/TheRealMilesLee/Truman-CS180-Documents/blob/master/Test%205.docx) This is the Mistake collection from test 2

[Test 6](https://github.com/TheRealMilesLee/Truman-CS180-Documents/blob/master/Test%206.docx) This is the Mistake collection from test 1, 2 3

[CS180 Coding Style Guide](https://github.com/TheRealMilesLee/Truman-CS180-Documents/blob/master/CS180%20C%2B%2B%20Language%20Coding%20Style%20Guide.pdf) This guide you how to code in appropriate way

[CS180 Notes](https://github.com/TheRealMilesLee/Truman-CS180-Documents/blob/master/CS180%20%E7%9F%A5%E8%AF%86%E7%82%B9%E6%A2%B3%E7%90%86.pdf) This is the knowledge point collection for the whole course, it is the most important documents that needs to be go through in this course

# External link

For the lab code: https://github.com/TheRealMilesLee/Truman-CS180-Course

You can access the course using Dr.Beck's website: http://borax.truman.edu/180/

About Dr.Beck: http://borax.truman.edu/

contact me: hl3265@truman.edu

About the Truman State University: https://www.truman.edu/

# Terms and concepts

This is the full term and the concepts notes in the Fall 2019, CS180 course.

#### Chapter 1

In this chapter, it just telling about the basics of how computer work, here is 5 important part that needs to be take care of:

1. Hardware components: What construct the computer

2. Main memory: the random access memory and its address

3. Kinds of values that can be stored in the memory: Like the integers, floating number and the string.

4. The language that be used to programming: For this course, we only learn C++.

#### Chapter 2

In this chapter, the variables and the data types were the two most important parts that we learned in this chapter. The data types is a set of values with a set of operations that defined values. In the C++ language, we have various values, e.g. integer, char, string, float, bool and so on.

Also, in this chapter, we mentioned about the operations that you can do in the c++ language. The unary minus, addition, subtraction, and the multiplication just work as the way you think. 

#### Chapter 3
 
In this chapter,the stream extraction operator is the most important part among this chapter, it reads data from standard input and converts it to the type of the variable. The mathematical operations are available from the <cmath> library, including the pow function. What's more the overflow and the underflow can result from arithmetic operations. Mix type to do the math is not recommend, if you really need to do that, please use the static_cast<> to cast the types.

For the formatting, output, you can use the setw(), fixed, setprecision() and the showpoint functions to reformatting the output files.

### Chapter 4

In this chapter, what your need to take care of is the relational operators and the bool type. The if, if-else, if-elseif-else were also the most important idea points in this chapter.

For the if statement, the logical operators is the another key part of this operators. For these operators, one should extremely take care of, that is the && operator and the || operator happens in the same if declaration. like, if you want to state "A equal to B or A equal to C" you should write "if (A == B || A == C)" instead of "if (A == B || C)".

And here is the truth table below:

![Truth Table](https://github.com/TheRealMilesLee/Truman-CS180-Documents/blob/master/Truth%20Table.png)

### Chapter 5

 This chapter is mostly telling about the loop structure. Two most important loop: while loop and the do-while loop. The while loop is a pretest loop, its body executes zero or more times. But the do-while loop is a post-test loop, it will always execute at least once, the do-while loop is more often used for input validation. You can control the loop with the boolean flags. Also, in this chapter, we also mentioned about the for loop. this loop is and only for the situation that you have already know the number of loop iterations. This loop is another pretestloop

 Never use "break" or continue with loops, NEVER return from a loop.

 If you want to open a file, you can use the ifstream to open it, and after you finish the file operations, don't forget to close the file

### Chapter 6

In this chapter, we talked about the functions and the function design. A function that can proper used must have function prototype, function body, parameters, Javadoc and the functions call in the main function.

Pass by reference & pass by value: The pass by reference is basically like a pointer that just a alias of another variable, the pass by value is get a copy of the variable.

#### Chapter 7

In this chapter, we talked about the array.In this section, for the arrray part, we need to know the way to declare and initialize the array and know the range based loop. Know the 
