## Title 
#### Exploring Functional Programming by Rebuilding Redux

## Abstract

The goal of this talk is to introduce basic functional programming concepts. This will be achieved by demonstrating how to rebuild [Redux](https://github.com/reactjs/redux), a popular Javascript library, using Ruby. For this purpose, I open-sourced a gem called [Rubidux](https://github.com/davidjuin0519/rubidux), which borrows the model from Redux.

## 簡介

Ruby不僅簡潔、優雅、易用，它還具有一些特性，可以讓我們使用一種古老的程式典範：Functional Programming。講者將透過實作一個著名的 Javascript Library: Redux，來示範如何使用 Ruby 實踐 Functional Programming。

Why Redux?
- 原始碼短小
- 大量使用
- 良好的文件

## Outline

1. #### What is functional programming (FP)?

  Functional programming is a paradigm of programming.

  Some features are:
  - Describe **what you want** rather than **how you do it**
  - Functions are first-class
  - Higher order functions => map, reduce, filter, compose, curry
  - Lexical closure
  - Referential transparency => pure function
  - Pattern matching
  - Lazy evaluation
  - No side-effects
  - Immutable data

  - Functiona are first-class
can be stored in variables and data structures
can be passed as a parameter to a subroutine
can be returned as the result of a subroutine
=> Higher-order function
=> map, filter, reduce, compose

  - recursion rather than iterative
  - immutability

2. #### Why is FP getting popular again?

  - Higher level programming language
  - Greater computing power compared to 50 years ago
  - Need for high concurrency application (immutability)
  - Big data (data pipeline infrastructures like Hadoop / Spark)
  
  ##### Can Ruby do functional programming?

  - Ruby is an elegant language
  - Ruby is inspired by LISP
  - Ruby has lambda

  So, yes, Ruby can do FP, technically.

3. #### Introduction to Redux

  Redux is a great choice to get going.

  - Use a lot of FP concepts
  - Tiny
  - Well documented
  - Increasingly used in Javascript apps

4. #### Demonstrating Rubidux

  Including FP concepts and skills such as:
  - Lambda
  - Compose
  - Curry
  - Map / Reduce
  - Lazy evaluation

5. #### Possible use case of Rubidux

  Providing state management for [Reactrb](https://github.com/reactrb/reactrb) (Ruby wrapper for React.js)

6. #### Takeaway messages 

  - Have a sense of using Ruby lambda
  - Know how to complement OO design with FP style
  - Contribute to Rubidux if you like it

The task is to build a data structure and provide some interface to update its data.
Can be done by function composition

Composability
How can we build a architecture by composing functions?
Explain why

1. Recursive Data Type

Reducers
A data type for values that may contain other values of the same type.
ex. list

The interface to update the data
Function is the data
Pure function
Analogy to BinaryTree
Use higher-order function to encapsulate

2. Make abstract data type
Store
A data type
Collect tools to manipulate the data structure
Dispatch
Subscribe
Replace reducer


3. Control the complexity
Middleware
Side effects
Remove the boilerplate code
composition
testability

### Why should this talk be considered?

1. Explore possibilities of ruby programming
2. Help ruby community advance Ruby skills
3. Introduce the next big-hit concepts for people who are interested in big data
4. Open-sourced gem for further contributions and help ruby community grow