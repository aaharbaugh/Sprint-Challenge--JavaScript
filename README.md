# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

    For Each does not change the array. Map creates a new array. 

2. What is the difference between a function and a method?

    A method is a part of an object. It can be called using the object itself. Like person.speak(). Whereas a function is standalone. 

3. What is closure?

    Closure is the term used to describe the scope of individual functions and were they are able to search for the variables they need. 

4. Describe the four rules of the 'this' keyword.

    Global Binding. when referencing this in global scope. You are referencing the window/browser/console object that contains all of the parameters, attributes of the window/browser/console.

    Implicit Binding. If you have a function within an object, when you call that function outside of the object, like: aaron.myFunction(), the object aaron is what this. references. 

    Explicit Binding. Similarly to implicit, however the binding is visible and external. Whereas implicit is hidden. 

    New Binding. When creating new functions or objects. Using the this keyword basically refers to the object that is being created. So each this.something is now an attribute being created in the object. 

5. Why do we need super() in an extended class?

    Super() is an abstraction of creating the parent objects. Passes the attributes back up to the parent class so that the object created can have same attributes as parents. 

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
