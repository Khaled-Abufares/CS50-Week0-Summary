CS50 Week 0: Introduction to Computer Science
> **بِسْمِ اللَّهِ الرَّحْمَـٰنِ الرَّحِيمِ**

Course Overview

CS50 is Harvard University's introduction to computer science and the art of programming. The course begins with Week 0, which covers the fundamental concepts that serve as a foundation for the entire course.

Key Concepts

Binary and Representation

Computers use binary (0s and 1s) to represent all data

Each binary digit is called a "bit" (0 or 1)

8 bits = 1 byte

"A single letter, like 'A', takes 1 byte of memory.”

ASCII is a character encoding system that uses 7 bits to represent 128 characters, mainly for English letters and symbols.

Unicode is a modern, extended encoding system that includes all ASCII characters and adds support for characters from all languages — such as Arabic, Chinese, and emojis.


So we can say: ASCII is a small part of the huge Unicode system, just like a Bit is part of a Byte.


Algorithms

An algorithm is a step-by-step procedure for solving a problem or accomplishing a task.

Example: Finding a name in a phone book


Imagine you're searching for a name like Kareem in a phone book.

With linear search (O(n)), you check each page one by one from start to end until you find the name. This could take a long time if the name is near the end.

With binary search (O(log n)), you take advantage of the alphabetical order by splitting the book in half, checking the middle, and repeating this process in the correct half each time — drastically reducing the number of steps.

This example clearly shows how algorithm efficiency is measured using Big O notation: Linear search grows with the size of the data, while binary search grows much more slowly, making it far more efficient when dealing with large data sets.

Pseudocode

Pseudocode is a human-readable way to describe the logic of an algorithm. It acts as a bridge between the idea (algorithm) and the actual code (formal implementation). You can also use pseudocode to clearly explain your approach to classmates, teammates, or interviewers, even if they don’t know the specific programming language you're using.
Example Pseudocode: 
1. Pick up phone book  
2. Open to middle of phone book  
3. Look at page  
4. If person is on page  
    Call person  
5. Else if person is earlier in book  
    Open to middle of left half of book  
    Go back to step 3  
6. Else if person is later in book  
    Open to middle of right half of book  
    Go back to step 3  
7. Else  
    Quit

Scratch Programming

Scratch is a block-based visual programming language developed by MIT, used in Week 0 to introduce programming concepts without syntax complications.

Key Programming Constructs Introduced in Scratch

Sequence: Executing instructions in a specific order

Selection (Conditionals): Making decisions using if, else if, else

Loops: Repeating instructions using repeat, forever, or while

Variables: Storing and retrieving data

Instead of telling the cat to say "Meow" directly every time, we can store the word "Meow" in a variable like this:

Set [sound] to [Meow]

Then we tell the cat: Say [sound]

Now, "Meow" is stored in memory, and the cat can retrieve it anytime — which is a perfect example of how variables work.

Events: Responding to user actions or program triggers

Functions (Custom Blocks): Creating reusable named blocks of code for cleaner, modular design

Problem Solving

Week 0 emphasizes a systematic approach to solving problems:

1. Understand the problem clearly


2. Break it down into smaller, manageable pieces


3. Design algorithms for each part


4. Implement the solution using code


5. Test and debug until the solution works correctly



Final Project

Students create a simple interactive program in Scratch that demonstrates:

Use of sprites and stage

Implementation of at least one condition, one loop, and one variable

Implementation of at least one custom block (function)

User interaction through keyboard, mouse, or other input


Key Takeaways

Computer science is about problem-solving, not just coding

Computational thinking involves breaking down problems into smaller, manageable parts

Efficiency matters in algorithm design

Programming concepts are consistent across languages, even if syntax differs


Resources

CS50 Week 0 Official Page

Scratch Programming Environment

Week 0 Lecture Notes

Problem Set 0


Note: This resource is extremely helpful for learning programming. However, it may contain background music or occasional images that are not appropriate. Please mute or avoid them as needed.

