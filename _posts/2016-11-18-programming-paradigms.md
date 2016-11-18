---
layout: post
title:  "Programming Paradigms"
date:   2016-11-18 13:50:00 +0100
categories: programming
---

Before diving in to programming paradigms, it's important to establish what computer programming actually is. Hoare states that a computer program is "a set of coded instructions that enables a machine, especially a computer, to perform a desired sequence of operations" (1969). Therefore, a programming language (or environment) is a way of constructing a set of "coded instructions" from which the computer can perform a task.

A programming paradigm is a style or "way" of programming. I want to try and attempt to categorise educational programming environments using traditional programming paradigms.

Peter van Roy categorised programming in to the following paradigms.

![van Roy]({{ site.url }}{{ site.baseurl }}/assets/vanroy.jpg)

The features relevant to educational programming that van Roy describes are as follows:

- Nondeterminism
	- The execution of the program is not completely determined by it's specification.
	- Different behaviours on different runs (makes an algorithm nondeterministic).
- State
	- "State is the ability to remember information, or more precisely, to store a sequence of values in time".
	- For example, incrementing a variable.
- Procedure
	- Amn independant module of code that fulfils a certain task and can be referenced from the main code.
- Concurrency
	- Performing more than one operation at one time.

The programming paradigms relevant to educational programming languages/environments.

- Declarative
	- Expresses logic of computation without describing flow control.
- Functional
	- Programming using evaluation of mathematical functions (telling computer what is needed) - avoiding changing state and mutable data.
- Imperative
	- Explicitly telling the computer what to do - contains state and mutable data.
- Procedural
	- Imperative programming with procedures.
- Object-oriented programming
	- Computation is effected by sending messages to objects, objects have state and behaviour.
- Constraint
	- Programmer specifies a set of constraints, and an engine infers the answers to questions.

**Sources**

Roy, P. Van, ‘Programming Paradigms for Dummies: What Every Programmer Should Know’, New Computational Paradigms for Computer Music, 2009, pp. 9–47, http://www.dmi.unict.it/~barba/PROG-LANG/PROGRAMMI-TESTI/READING-MATERIAL/VanRoyChapter.pdf.

Hoare, C. A. R., ‘An Axiomatic Basis for Computer Programming’, Communications of the ACM, 12:10 (1969), pp. 576–580.

[http://cs.lmu.edu/~ray/notes/paradigms/](http://cs.lmu.edu/~ray/notes/paradigms/)
