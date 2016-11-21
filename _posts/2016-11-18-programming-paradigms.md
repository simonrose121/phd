---
layout: post
title:  "Programming Paradigms"
date:   2016-11-18 13:50:00 +0100
categories: programming
---

Before diving in to programming paradigms, it's important to establish what computer programming actually is. Hoare states that a computer program is "a set of coded instructions that enables a machine, especially a computer, to perform a desired sequence of operations" (1969). Therefore, a programming language (or environment) is a way of constructing a set of "coded instructions" from which the computer can perform a task.

A programming paradigm is a style or "way" of programming. I want to try and attempt to categorise educational programming environments using traditional programming paradigms.

Peter van Roy categorised programming in to the following paradigms:


![van Roy]({{ site.url }}{{ site.baseurl }}/assets/vanroy.jpg)

**Key Features**

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

Nondeterminism isn't found in educational programming environments due to it's unpredictability. Novice programmers (particularly children) find it a difficult to understand that an identical program do something different on each execution.

State, which variables and mutable data, are included in environments such as Scratch. Dealing with data (and therefore state) is described as a key element of computational thinking.

Some more complex environments, such as Snap! (Berkeley's procedural extension to Scratch) and Wonder Workshop's Blockly application for it's Dash and Dot robots allow the use of procedures.

Concurrency is found in most educational programming environments. Blocks of code can be run on the same start event (mimicking concurrency, if not at a computational level) and event listeners can fire code simultaneously depending on the program structure. [ToonTalk]({{ site.baseurl }}{% post_url 2016-11-04-toontalk %}) uses the concurrent constraint paradigm, in which goals are satisfied concurrently (this interesting uses nondeterminism).

**Relevant Paradigms**

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
	- Objects can inherit actions from other objects.
- Constraint
	- Programmer specifies a set of constraints, and an engine infers the answers to questions.

**Categorisation of Tools**

I have tried to categorise the tools I have reviewed in previous weeks in to programming paradigms (main article can be found [here]({{ site.baseurl }}{% post_url 2016-10-31-programming-tools %})).

*Declerative*

*Functional*

- [Lightbot]({{ site.baseurl }}{% post_url 2016-11-05-lightbot %})
- [Kodable]({{ site.baseurl }}{% post_url 2016-11-06-kodable %})
- [Bee-bots]({{ site.baseurl }}{% post_url 2016-11-05-beebots %})
- [ToonTalk]({{ site.baseurl }}{% post_url 2016-11-04-toontalk %})

*Imperative*

- [Scratch]({{ site.baseurl }}{% post_url 2016-11-02-scratch %})
- [Scratch Jr]({{ site.baseurl }}{% post_url 2016-11-04-scratchjr %})
- [Hopscotch]({{ site.baseurl }}{% post_url 2016-11-08-hopscotch %})
- [Espresso Coding]({{ site.baseurl }}{% post_url 2016-11-06-espresso-coding %})

*Procedural*

- Snap
- [Dash & Dot (Blockly & Wonder)]({{ site.baseurl }}{% post_url 2016-11-09-dash-and-dot %})
- [Turtle Logo]({{ site.baseurl }}{% post_url 2016-11-02-logo %})
- [Stagecast Creator]({{ site.baseurl }}{% post_url 2016-11-05-stagecast-creator %})

*Object-Oriented*

- GameMaker

The lack of declerative tools indicates the neccessity of teaching flow of control, or the order in which individual statements are executed. This allows children to predict the outcome of certain tasks.

Functional tools contains programming games Lightbot and Kodable, despite having programming concepts such as conditionals and procedures, do not hold program state, or mutable data items.

Imperative tools include Scratch and other programming tools that have both state and data, along with the other common programming concepts.

The procedural tools are imperative with the addition of procedures, which can be called to execute repeat behaviour. The only tool that provides true object-orientation (including inheritance and polymorphism) is GameMaker.

**Further Questions**

How do the programming paradigms relate to the pedagogy of the tools?

**Sources**

Roy, P. Van, ‘Programming Paradigms for Dummies: What Every Programmer Should Know’, New Computational Paradigms for Computer Music, 2009, pp. 9–47, http://www.dmi.unict.it/~barba/PROG-LANG/PROGRAMMI-TESTI/READING-MATERIAL/VanRoyChapter.pdf.

Hoare, C. A. R., ‘An Axiomatic Basis for Computer Programming’, Communications of the ACM, 12:10 (1969), pp. 576–580.

[http://cs.lmu.edu/~ray/notes/paradigms/](http://cs.lmu.edu/~ray/notes/paradigms/)
