---
layout: post
title:  "Small Basic"
date:   2016-11-06 15:27:00 +0100
categories: programming
---

![Small Basic]({{ site.url }}{{ site.baseurl }}/assets/smallbasic.png){:width="500px"}

Small Basic is a simplified variant of the BASIC programming language.

**Key Features**

- Simple but complex
	- The language only has 14 keywords.
	- However, it allows for object-orientation.
	- The standard library includes basic classes for mathematics, string handling and I/O.
- IDE
	- It comes with a built in simple IDE.
- Turtle graphics
	- Built in "Turtle" graphics library taken from Logo (and employing the same constructionist principles).
	{% highlight smallbasic %}
	For i = 1 to 4
	  Turtle.Move(100) ' Forward 100 pixels
	  Turtle.Turn(90) ' Turn 90 degrees right
	EndFor{% endhighlight %}
- Online curriculum
	- Microsoft supply an online (and downloadable) curriculum to explain the key concepts of the language.

**Sources**

[http://social.technet.microsoft.com/wiki/contents/articles/16982.small-basic-curriculum-online.aspx](http://social.technet.microsoft.com/wiki/contents/articles/16982.small-basic-curriculum-online.aspx)
