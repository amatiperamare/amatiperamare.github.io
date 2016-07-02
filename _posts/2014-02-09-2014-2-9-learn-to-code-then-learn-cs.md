---
title: Learn C, Then Learn Computer Science
date: 2014-02-09 00:00:00 Z
layout: post
summary: Theoretical understanding is great, but fundamentals are just as important.
---

I'm an undergraduate studying computer science. It's great to get to sink my teeth into interesting, high-level problems like machine learning algorithms and graph theory, but I feel like my formal CS education isn't touching on some of the fundamentals of how computers work and how to write good code.

In his post "[Learning to Code vs. Learning Computer Science](http://shkspr.mobi/blog/2014/02/learning-to-code-vs-learning-computer-science/)", Terence Eden raises some excellent points about the importance of learning the algorithms and intellectual principles behind programming. However, while I agree that "no conversation about teaching coding in schools is complete without a theoretical understanding of the science behind the code", I also think that it's important to talk about students' understanding of the *mechanics* behind the code.

I'm a 3rd-year computer science student with more experience than most. I learned to program in middle school, writing tic-tac-toe programs in TI-BASIC on a graphing calculator. I've also spent three years as an engineering intern at a local computer vision and signal processing company. This puts me in the interesting position of being able to compare what my college computer science/software engineering courses are teaching me versus what my personal explorations and work experience have taught me.

As a first-year CS student at the University of Southern California's school of engineering, my CS-101 professor spent a week or two making sure everyone understood the basics of control structures and C syntax, then jumped straight into a detailed and thorough course on the underlying mechanics of code. All our work was done in C, and we went over how memory was addressed and structured, heap memory vs stack memory, the functions of the preprocessor, compiler, and linker, and fundamental data structures like linked lists. While most of this was review for me, some of it wasn't - as an intern, I had never bothered to think about exactly how pointers functioned at a hardware level, and I'd never implemented any of my own data structures, since they were always provided by a library. I appreciated the chance to re-learn coding from the ground up - but balked when I realized that USC's program would have me grinding on the same kind of relatively low-level mechanics for the first 3 years of my degree. It was a program that would have made me a great coder, but one which would have failed me as a student of computer *science*.

I ended up transferring to a new computer science program at a small liberal arts school in Portland, OR. I was pleased to find that programming courses at Lewis & Clark were heavy on theory and high-level concepts. I wouldn't have to wait until the second semester of my senior year to take an AI course or study programming language design. But in my classes, I started to notice something odd. In the few courses that were taught using C rather than Java, my classmates would find my code hard to grasp. I got lots of questions about basic C features like structs. This semester I used function pointers in an assignment and later heard them described as "Quinn's magic C voodoo". 

This was confusing - my classmates were juniors and seniors who were 3+ years into a computer science degree, yet many of them didn't seem to have an understanding of how computers worked. They could write high-level code and analyze algorithms, but had never used malloc.

It turned out the the two required intro CS courses at my new school only dealt with the very basics of control structures and boolean logic before jumping into high-level object oriented programming in Java. Students writing code in C were told never to use malloc, and didn't have an understanding of the difference between stack and heap variables. 

This is the problem with emphasizing computer science over learning to code. Without an understanding of what's happening at a low level, my peers ran into issues like C segfaults and Java NPEs and had no idea what to do to debug them. This is a problem that stems from teaching people computer science but not teaching them how to code. Learning to code isn't just teaching people how to spell - it's teaching people the meaning behind the words. That's why I think "learning to code" is just as important as computer science to teach - and teach well - at an undergraduate level.