---
layout: page
title: Notes
permalink: /notes/
toc: true
---

{% include toc.html %}

## Capture Information Plan
I plan to store all new information that I learn in this notes page for the rest of the trimester. This will mostly be the info I learn about java from code.org or personal research

---

## Syntax for Front Matter

![Screen Shot 2022-08-25 at 1 58 36 PM](https://user-images.githubusercontent.com/24465360/186767931-d47f4cb3-6c7c-4d68-8b51-8bd6ee659f86.png)

--- 

## Code.org Documentation

### Lesson 1
Lesson 1 is simply an introduction to the course. It talks about how CSA students are taught to think similarly to software engineers, and how we will continue to grow form this.

### Lesson 2
 In lesson 2, we learn about the basic structure of a java header, as well as some basic syntax. Below is a basic java header.

 ```java
public class className {
  public static void main(String[] args) {
  
  }
}
 ```
 
 - The ```main``` method is the most common method used as an entry point to any java program. 
 - The ```public``` method is simply a method that makes the scope of the code global. It's kind of in the name.
 - ```static``` means that there will only be one type of this method and that it will be shared. Basically, we can call the ```main``` method multiple times without creating a new object.
 - ```void``` means there will be nothing returned from the ```main``` method.
 - ```String[] args``` - The ```main``` method's argument is an array of ```string``` type. THis allows the method to accept command line arguments, which are stored as ```string```s in this variable. ```args``` can be changed.

### Lesson 3
To instatiate a new object you use the syntax: ```className objectName = new className();```

### Lesson 4
Lesson 4 was just lots of tedious programming challenges using the things we already learned from the first 3 lessons. There were 4 different challenges where we controlled a painter. These challenges made it almost muscle memory to call objects in java.

### Lesson 5
Lesson 5 was similar to lesson 4, by having many challnges to complete, except now the ```if``` statement was introduced. 

### Lesson 6
We learned about subclasses and superclasses. A subclass is a class that has its own attributes, but will inherit all of the attributes from a superclass. The way to construct a subclass is below:

```java
public class SubClassName extends SuperClassName {
  public SubClassName() {
    super();
  }

}
```

### Lesson 7
In lesson 7 we learn about creating new methods. The way we can do this is below:

```java
public void methodName(){ //create a method
  // put code that you want the method to run
}

variableName.methodName(); //to call the method
```

Important sidenote: In javalabs on code.org, you have to extend your subclass to the superclass "Painter" in order to use most of the prebuilt features.

### Lesson 8
In lesson 8, we learn about commenting code using ```//``` or ```/* */```. We also learn about commiting files, which are then stored in the backpack. These files can be imported once again from the backpack. We learn about opening code reviews where peers can see and comment on our code (But these have to be enabled by the teacher, which they are presently not). 

### Lesson 9
In this lesson the ```while``` loop was introduced. Everything else was very standard, and simply challenged us to use the while loop.

### Lesson 10
This lesson introduced logic gates. ```!``` is the NOT operator. ```&&``` is the AND operator.

### Lesson 11
This lesson was just a few basic debugging chhallenges. We would look as dysfunctional code and try to figure out what was wrong with out. Nothing new in this lesson, just review.

### Lesson 12
This lesson challenged us to make new slighty more complicated methods, but once again, nothing really new.

### Lesson 13
I could be entirely misunderstanding, but I could not for the life of me figure out this lesson. It seemed bugged, as there was no paint for the painter to use. I did some research and I'm quite lost, but the concept was just to create and save a method in a new file so it could be used across projects.

### Lesson 14
This lesson branched off 13 a bit with the concept. To be honest the last few lessons are very repetitive and no new info was really taught.

### Lesson 15
The final lesson was simply a FRQ asking about your best software engineer qualitly. Not a real lesson.

### Boolean Expressions
* Operators
  * ```==``` Equal to
  * ```!=``` Not equal to
  * ```<``` Less than
  * ```<=``` Less than or equal to
 
 * Compound Boolean Expressions
   * Nested if statements: ```if``` statements within ```if``` statements
 * Logical Operators:
   * ``` &&``` AND
   * ```||``` OR
   * ```!``` NOT
 
 * Short circuited evaluation - A compound boolean expression can have a determined outcome based on just a few operators
 * De Morgan's Law
   * Dictates that a ```NOT``` statement changes an ```AND``` to an ```OR``` and vice versa.

---

## Class Notes
