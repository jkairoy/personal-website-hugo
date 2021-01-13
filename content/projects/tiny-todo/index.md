---
title: "Tiny Todo"
description: "Creating a todo app that cuts out the hassle by organizing your work for you"
tags: ["DESKTOP APPLICATION ENGINEERING"]
category: "Personal Project"
tech: ["React.js", "Electron"]
team: "1 Full Stack Engineer (Me)"
date_string: "February 2019 (1 week)"
---
<section>

### The Goal

To quickly learn about developing for desktop with Electron while making a useful todo app

</section>

<section>

### The Design

<article>

The main idea behind TinyTodo was that you should be able to write down nearly anything you have to do, and TinyTodo
would know how to sort your items for maximum mental clarity. I saw this being best achieved through the recognition of
dates and times, and by allowing users to input priority (i.e. #2). I decided that these functions should be made clear
to the users intuitively, and thus I decided to implement text highlighting on application recognition of certain
strings. Finally, I decided to have a “done” list that todo items would be moved to after completion. I saw this as
having two functions, giving the user the option to undo an accidental click, and allowing users to see how many items
they have completed, making the application a bit more satisfying to use.

<aside>

![Example warning](singletab.png)

</aside>

</article>

</section>

<section>

### The Execution

The execution of the app was fairly simple, the most challenging part being accounting for all of the parsable strings.
Standard Javascript regex was used to recognize appropriate strings and combinations of strings and thus assign priority
numbers to them. In general, this algorithm prioritized date first and user assigned importance over time differences
less than a day ahead. If you want to check this out in more detail, view
my [github project](https://github.com/jkairoy/tinytodo).

</section>

<section>

### Takeaways

This project was definitely a worthwhile exploration into the capabilities of Electron and it surely opened the door to
many projects to come. It was also a valuable experiment in responding to user feedback as I was able to iterate the
application as my friends gave me their insights.

</section>
