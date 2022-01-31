# Log Day 1 to 30

## Day 0

### Goal Setting

- Invest a minimum of 1 hour per day
- Properly learn basics of C# and .NET 
- Create own project with C# (pick idea from the internet or come up with own project)
- Learn advanced skills for C# 
- Improve C# LINQ skills
- Learn about Design Patterns
- Improve Clean Coding approaches
- Work on Unit Test writing skills
- Learn more about other technologies that come in handy in work environment (Kibana, Docker etc.)

### Approach

- Quickly going through PontWitt C# Beginners Course
- Picking additional online courses
- Pick a project to implement

## Day 1

- The first thing I approached was setting up my work environment on the PC I am using
  - Visual Studio with all necessary Tools
  - Created a new GitHub account
- Chapter 1 to 3 of the C# Beginners Course 
  - What is C#? What is .NET?
  - Differences between .NET Framework and .NET Core
  - Little programming

## Day 2

- Work on C# Beginners Course (Chapter 4 - 9)
  - Repetition of Syntax and Structure
  - Information about Visual Studio Shortcuts
  - Start of Mini-Project Hangman
- Conclusion 
  - Course might be a bit too easy for my skill level
  - Good repetition of key factors though
  - As you can get through the course quickly, it does no harm to finish it and take note of things I have not heard before (or cannot remember)

## Day 3

- Work on C# Beginners Course (Chapter 10 to 15)
- Nothing new, just the basics and work on the Hangman Mini-Project

## Day 4 

- Work on C# Beginners Course (Chapter 16 to 21)
- Work on the Hangman Mini-Project 

## Day 5

- Finish C# Beginners Course (Chapter 22 - 25 + Bonus Chapter)
- Finish Hangman Mini-Project
  - Make adjustions more than the Course required :)
- Looking for a new course to start on day 6

## Day 6

- Started with *C# Advanced Topics* on Udemy
- Chapter 1: Generics; I learned the following things (or took note of them)
  - why generics are prefered over boxing to object (performance, of course)
  - constraints are used when methods are implemented that do not work for all possible objects
  - generic methods can exist in non-generic classes
  - there are different types of constraints: interfaces, classes and their subclasses, value types, reference types and objects with default constructors
- Chapter 2: Delegates
  - I put a lot of focus on this topic because I had always trouble with these
  - I coded alongside the example in the video to create delegates and try the standard .NET framework delegates
  - Other learnings:
    - what are delegates (references on how to call methods or method groups) and what are they useful for (e. g. frameworks)
    - the .NET framework already includes the Action and Func delegate
    - prefer Delegates over Interfaces if the caller does not need access to other properties/methods or for eventing design patterns

## Day 7

- Chapter 3: Lambda Expressions
  - Basic repetition of how Lambda Expressions work; not a lot of new or difficult things
- Chapter 4: Events and Delegates
  - This topic was very interesting. The instructor put a lot of effort into explaining how events work behind today's EventHandler.
  - Started out by implementing an event handler with a delegate and event instead of using the .NET framework EventHandler delegate right away

## Week 1 Recap

- It's great to take an hour of each day to repeat and enhance my knowledge of C#. I'm consistent with the one hour per day.
- Sometimes it's difficult to squeeze the hour in. I often find myself only doing it right before bed, which I want to improve in week 2.
- I repeated a lot of knowledge this week but also learned new details that I wasn't aware of or had forgotten (like how events work at the basis or how delegates actually work ...) 
- I want to find a project soon that maybe I could work on on the weekends parallel to the courses or latest after I'm done with the courses I want to do. But I don't want to start the projects only in the end, so would like to start earlier and build the project upon things I learn/repeat.

## Day 8
- Chapter 5: Extension Methods
  - How to use and when to use
- Chapter 6: LINQ
  - Combine LINQ with Lambda Expressions
  - Where LINQ can be used
- Coding Examples
- Brainstorming for a C# project to do within the 100 days

## Day 9
- Chapter 7: Nullable Types
  - basically repetition
- Chapter 8: Dynamic
  - super interesting as I have never used dynamic types before
  - the type of a dynamic variable can only be changed by assignment or if implicit conversion is possible
- Chapter 9: Exception Handling
  - catch order: from most to least specific (so catch(Exception ex) is always last)
  - the finally block can be replaced if "using" is used
  - always try to wrap exceptions, so the user only sees relevant information; only the people who are fixing the errors should see the full stack trace
