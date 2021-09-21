# Functional Programming Concepts

1. What is functional programming?

Functional programming: is a programming paradigm, a technique for building the structure and elements of computer programs, that treats arithmetic as an evaluation of mathematical functions and avoids changing state and mutable data.

2. What is a pure function and how do we know if something is a pure function?

The first basic concept that we learn when we want to understand functional programming is pure functions. So how do we know if a function is pure or not? Here is a very strict definition of purity:
* Returns the same result if given the same arguments (also referred to as an imperative)
* Does not cause any noticeable side effects

It returns the same result if given the same arguments
Imagine that we want to implement a function that calculates the area of a circle. The impure function will take the radius as a parameter, and then calculate the radius * radius * PI

3. What are the benefits of a pure function?

The code is definitely easy to test. We don't need to mock anything. So we can unit test pure functions with different contexts:
* Given parameter A → expect the function to return the value B
* Given parameter C → expect the function to return the value D
A simple example would be a function that receives a set of numbers and expects to increment each element of that set.

4. What is immutability?

When data is immutable, its state cannot change after it is created. If you want to change an immutable object, you can't. Alternatively, you can create a new object with the new value. In JavaScript, we commonly use a for loop. This following statement has some variable variables.

5. What is Referential transparency?

Reference transparency, a term commonly used in functional programming, means that with a function and an input value, you'll always get the same output. This means that there is no external case used in the function.

#Node JS Tutorial for Beginners

1. What is a module?

A module is a program component or part of a program that contains one or more procedures. One or more independently developed modules make up the programme. An enterprise level software application may contain several different modules, and each module serves unique and separate business processes.
