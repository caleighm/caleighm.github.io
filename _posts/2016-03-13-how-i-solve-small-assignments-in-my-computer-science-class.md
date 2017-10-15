---
id: 169
title: How I solve small assignments in my computer science class
date: 2016-03-13T14:22:49+00:00
author: Caleigh
layout: post
guid: http://caleighm.com/?p=169
permalink: /2016/03/13/how-i-solve-small-assignments-in-my-computer-science-class/
categories:
  - Learning strategies
  - Programming how-to
---
<figure><img src="{{ site.baseurl }}/public/posts/chewed.jpg" alt="Millie chewed up some old headphones. She doesn't recommend listening to music while programming." sizes="(max-width: 375px) 100vw, 375px" data-recalc-dims="1" /><figcaption>Millie does not recommend listening to music while programming, unfortunately. Too distracting.</figcaption></figure> 

Right now I&#8217;m enrolled in [CISC 124](http://courses.caslab.queensu.ca/cisc124/), a first-year computer science course at Queen&#8217;s on object-oriented programming in Java. This is the third computer science course I&#8217;ve taken at a university level. In every course so far, instead of writing one massive essay at the end of term like in my past life of English literature, the professor requires us to write many small computer programs and submit those throughout the term. (There may also be midterms and exams, but those are not the purpose of today&#8217;s post!).

This week, I finished writing my fourth program for this course, and I want to share the strategies I&#8217;ve found helpful so far. Keep in mind that these strategies probably best apply to small programming assignments as opposed to actual projects, and I&#8217;m always learning more about the process!

# Rewrite the instructions

In CISC 124, the assignment prompts tend to be pretty wordy. I like to read through the prompt and actually re-write what&#8217;s important on a separate piece of paper. I tend to do this in a visual way; I use mindmaps to signify the relationships between different classes and methods (the ignorant student&#8217;s version of UML!), and I create tables that compare the purpose of each method if some of them are pretty similar. I need to be able to explain, in my own words, what the program I&#8217;ve been assigned to write actually has to accomplish.

This step is less important for simple assignments that I can immediately wrap my head around, but for assignments with parts or algorithms that I&#8217;m not 100% on yet, I find this step is surprisingly helpful. I&#8217;ve come to realize that I am very bad at mental visualization, so verbalizing in words and writing things down is a lot easier for me than trying to imagine mentally. (I learned a lot more about visualization from _[The Mind&#8217;s Eye](http://www.oliversacks.com/books-by-oliver-sacks/the-minds-eye/)_ by Oliver Sacks &#8212; very cool, check it out.)

# Shuffle a deck of cards in your hands

Okay, this is maybe one of the weirder strategies I&#8217;ve come up with. I mentioned above that I find visualization pretty difficult. This makes imagining even basic search algorithms tricky for me. The best way I found to combat this, weirdly enough, was to pretend that I was actually holding a deck of cards (a real-world array!) in my hands and sorting them according to the algorithm. This helped me articulate what was actually happening in the algorithm so that I could then write it in a program.

When I first started using nested for loops, I used this same method. I never actually needed to hold objects in my hands for it to work; it was enough to move my hands around and pretend I was shuffling things. I found this physicality a lot easier than completely imagining what was going on. I think this is why I find math so much easier to do on paper than in my head.

# Code with a plan

When I first started writing these assignments, I&#8217;d often dive right into the coding part without taking some time to plan the program&#8217;s structure. Now that we&#8217;ve covered polymorphism in CISC 124, though, I find it much more helpful to plan out the program in advance &#8212; how will I break down the methods, classes and variables in a way that makes sense. I normally do this on a piece of paper. This helps me avoid a lot of refactoring or debugging from careless, avoidable errors.

On my latest assignment, it was extremely satisfying that I was able to compile and run the whole program successfully after just one go, passing all my tests. The saying is &#8220;measure twice, cut once,&#8221; and it applies equally to coding!

# Move from top to bottom

When I want to work a little more quickly, sometimes I&#8217;ll cheat by doing the planning directly in the .java files as opposed to a piece of paper. I&#8217;ll create all the headers for the classes and methods, and include in comments what each one should take as a parameter and what it should return. Then I can start filling in the blanks.

There is something very pleasing about finishing up a program&#8217;s skeleton like this! I always got a similar feeling when I finished outlining a paper, but before I started writing it. It&#8217;s sort of like, &#8220;Okay, the assignment is now _basically_ written, right?&#8221; You get a nice sense of the assignment as a whole, and filling in the gaps doesn&#8217;t seem as tall of an order anymore.

# Talk to yourself if you get stuck

Sometimes, despite all my planning, I&#8217;ll still get a little stuck on something. This normally happens when it&#8217;s a concept I didn&#8217;t pay much attention to in-class (likely because I was tired, thinking about something else, or missed the lecture for work). My go-to solution for this is always to talk out loud to myself. I do this for math problems, too. Starting at a point in the program where I feel confident in my code, I&#8217;ll talk myself through what is happening.

Sometimes, it&#8217;s the syntax that throws me off instead of the concept (a prime example is Comparators from this past week). In cases like that, I&#8217;ll talk out loud in pseudo-code about what I _want_ the program to do, write down that articulation, and then look through the professor&#8217;s sample code or lecture slides for something that looks like it might be able to accomplish (or be tweaked to accomplish) my end goal.

So far, at least, this has always worked. I&#8217;ve come to rely on this a lot in my darkest coding moments.

# Revisit the assignment instructions

Whenever I finish the assignment, I have a little dance party with the dog. But I don&#8217;t stop there. I always make sure to look back at the assignment instructions, and this time I treat the instructions as if it&#8217;s a checklist. After every sentence, I ask myself &#8220;Did I do this in the assignment?&#8221; If I&#8217;m at all unsure, I review what I wrote and revise as needed.

The more complicated the assignments get, the more this step becomes essential &#8212; it&#8217;s very easy to miss something small. For example, in this latest assignment, there was one little sentence toward the end that said all our variables should be private or protected. Easy to miss &#8212; but very important!

* * *

I haven&#8217;t done much research into why these strategies work for me. I think it has something to do with the limitations of working memory and my personal coping mechanisms for being terrible at mental visualization. Maybe that&#8217;s a blog post for another time.

On another note, I&#8217;m sorry I missed a blog last week! The week flew by and I forgot all about my commitment to a weekly blog.

&nbsp;