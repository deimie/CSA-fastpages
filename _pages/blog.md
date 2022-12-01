---
layout: page
title: Blog
permalink: /blog/
---

### Week 14
We did FRQ2 this week. It's kinda similar to FRQ1 but with some different methods and data points. I managed to get the tester and toString method working, but overall, I did not have the time to finish lots of the criteria.

### Week 13
This week we had to do FRQ1 from collegeboard. I learned about this complicated algorithm called Zeller's rule which helps find the day of the week for any given date. In Zeller's rule, the first month of the year is also march and the last is february. For the actual work completion, I managed to finish all the methods, but I only have the 1 original endpoint, as I was struggling with understanding weird syntax stuff.

### Week 12 - Finals Week
**Test corrections-**

![Screen Shot 2022-11-09 at 8 30 27 AM](https://user-images.githubusercontent.com/24465360/200886290-dad002ad-eaf8-4aa0-bdb0-88bacb0954ce.png)

**Q17-** Only values in arr at the start of the iteration will be in arr when the loop terminates. The value 8 is not in arr at the start of the loop. To avoid an ArrayIndexOutOfBoundsException from being thrown, the loop terminates when k has the value arr.length – 1, therefore the element at arr[arr.length – 1] is never assigned a new value.

**Q20-** Since j and k start at valid indices of nums with j being less than k, and since j is being incremented and k is being decremented in the body of the loop, eventually j will be greater than or equal to k without either becoming an invalid index so an ArrayIndexOutOfBoundsException will not occur.

**Q23-** List is an interface, which an ArrayList implements. Please note that List is no longer tested as part of the AP CSA exam and ArrayList will be used instead. This would be the case if the loop condition was k > 1 rather than k > 0.

**Q31-** Passing a reference parameter results in the formal parameter and the actual parameter being aliases. They both refer to the same object. Any updates made to the referenced array when mystery is called are being made on the single array that is reference by both data and values. When data[k + 1] is updated, this value new value should be used in the subsequent calculations.

**Q34-** Choice I uses the no parameter Point constructor to assign center a new Point with x and y both equal to 0, instead of x assigned the value a and y assigned the value b. Choice II correctly uses the two parameter Point constructor to create a new Point with x assigned the value a and y assigned the value b.

**Q39-** The value of recur(6) is 12. However, this call was made within another recursive call and is not the final return value

### Week 11 - Project Week 4
Earlier in the week we made the frontend much more functional, connected it to the backend, and we have a working databse that can add inputs (it can't remove them yet). On thursday we had our N@TM. Most people that didn't take CSA looked pretty confused by our project, as it was pretty raw looking, but Mr. M liked the database so that's cool.

### Week 10 - Project Week 3
Instead of doing student lessons, the curriculum was transitioned over entirely to working on our projects to prepare for N@TM. So far, our project is pretty underdeveloped, so we still have to connect our front and backends with an API and implement a database mostly. Our frontend is pretty bad looking too, but that's not my job.

### Week 9 - Project Week 2
We were supposed to have a bunch of lessons this week but things really fell apart so theres a bunch of stuff that didn't happen. I was also out sick for most of this week, so I missed all the lessons... anyways here's some of the code HW that I did with Calissa: [HW](https://deimie.github.io/fastpages/2022/10/24/unit4-hw.html).

### Week 8 - Project Week 1
This week we had a lesson on using Java objects. Here's the [homework](https://deimie.github.io/fastpages/2022/10/18/22-unit3-hw.html). We mostly worked on project stuff this week.

### Week 7 - Arraylists
This week we're being taught about arraylists. Funny enough, my group's topic which we have to present is arraylists, so we kind of already knew everything. This week was also dedicated to learning how to connect a frontend and backend server with an API. For the time being, I still have to fix our broken backend and create a frontend as the DevOps. 

### Week 6 - Project Approval
Okay so this week we had to finalize and present our idea for our project. We decided on making a sort of class manager where students log in with their github usernames. This means that the teacher can access students and their github accounts easily. We also have to practice connecting an API to our frontend. I just quickly did a covid API and it just prints out some JSON data.

### Week 5 - Design Starters
This week was all coding challenges from Mr. M. The main one was running a fibonacci sequence using classes in Java. I did that [here](https://deimie.github.io/fastpages/2022/09/22/fibonacci-java.html). We also practiced using javascript to manage JSON data and create HTML elements with javascript methods. Examples [here](https://deimie.github.io/fastpages/2022/09/21/js-notes.html).

### Week 4 - FRQ No. 1
This week, me and Calissa worked on 2 FRQ problems together. I was mainly in charge of FRQ question 2 on the 2019 APCSA collegeboard test. My in-depth solution to the problem is [here](https://deimie.github.io/fastpages/2022/09/19/unit1-lesson.html).

### Week 3 - Backend Development

This week we had to work on a lesson for java conditionals, and I also decided to add documentation about De Morgan's law. The basic run down is that an ```if``` 
statement will return an output if a set condition is met. An ```else if``` statement will execute if it's own condition is met so long as the 
intial ```if``` statement's condition was not met. An ```else``` statement has the final say at the bottom of the block meaning that if no other conditions were met,
it will output. ```else``` and ```else if``` do not need to be included however, and the ```if``` statement can be used alone.

De Morgan's law is the principle that applying ```NOT``` logic to ```AND``` logic will flip it to ```OR``` logic. The same is true in reverse.

This week we also had our human day where we discussed how happiness is mostly a choice. A good amount of the happiness we derive comes from the choice to be happy. 
There are of course scenarios that help with promoting happiness such as wealth or success. At the end of the day, it's all down to the person. Personally, having enough
money to get by boosts my happiness, but money is certainly not a huge priority in this case. Often times people with too much money end up losing personal connections  
and relationships with people they once knew well. All in all, happiness is a very fickle thing that will always remain important to try to maintain in whatever way
works best for you.

### Week 2 - Using Objects

This week is lots of code.org work. We're learning basically how to program in java. Lots of info on code.org documentation in the notes page. We had to create a GUI using java in a jupyter notebook. All grading will be done by reviewing our jupyter notebooks in fastpages.

### Week 1 - Innovation Pair Focus

This week we learned about primatives, which are a datatype in Java. More info on primitaves in posts. Talked about practicing pair programming, where 2 people program and share code frequently to build off each other. Mostly, I've been setting up fastpages and I implemented a dark mode. Working on a weird post icon formatting issue as well.

### Week 0 - Introduction and Tools

This week we worked on setting up our tools for the rest of the trimester. We talked about how we will begin with making real-world projects that serve actual functions. These projects will manage databases in backened. Assignments will be due on either Fridays or Mondays depeding on the criteria. We will be using slack, jupyter notebooks, github pages, vscode, and AWS.
