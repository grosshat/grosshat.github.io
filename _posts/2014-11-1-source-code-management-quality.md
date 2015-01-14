---
layout: post
title: Source Code Management Quality
comments: true
permalink: source-code-management-quality
---

When you write code, in a team or just as a single developer, you get a lot of
benefits using a Source Code Management (aka Version Control) tool. 
When you start to use it, you don't even know how you survived before. Version
Control System (VCS) records changes to file/s over time so that you can recall 
specific versions later. It helps a lot giving you an structured way for
managing changes, naming them, tagging them and sharing them with other
developers. Despite its importance, there is often a **lack of taste** for VCS
management among developers. Let's see some of them.

---

Bad Titles
----------
Too often the **commit moment** is understood, or at least felt, as a mere
formality. That means a tree full of bad titles and poor or just empty
descriptions, very hard to read later. Title and description should help to read
and search over the tree without the need of reading directly the code.

Look at these real examples and try to imagine how you would read a tree full of
commits like these without feeling you are reading a boring ass story.

    commit 7f6bba884f8bf417d7ea25bb6ae106180cdcdbb2
    Author: developer <developer@boring.com>
    Date:   Tue Apr 15 12:06:19 2013 +0200

        Update view

    commit 9f6bba884f8bf598d7ea25bb6ae106180cdcdbb4
    Author: developer <developer@boring.com>
    Date:   Wed Jun 10 9:06:19 2013 +0200 

        testing 1

    commit 4f6bba884f8bf345d7ea25bb6ae106180cdcdbb7
    Author: developer <developer@boring.com>
    Date:   Mon Feb 7 14:06:19 2013 +0200 

        update plugin.php, monday 7 


Non-English Language
--------------------
English is the language for writing code. Dot. Your code, your comments and
everything related to such stuff should be always in english. It does not matter
how much or how little you know and the quality of your english sentences and
vocabulary. The more you use it, the more you know. The goal is to read, write
and think just in one language, and do not have to move between different
languages depending on the thing. Some people works the following manner (I use
spanish since it is my native language):

- spanish for comments 
- english for variables
- spanish for file names
- english for function names
- spanish for commits
- english for external libraries

That is crap. Stop to do it. It is unsane and it does not help your career.
Writing code, building programs is a very communicative activity, requiring much
of the time cultivating good writing manners. And it is very hard to do that
writing pieces in one language surrounded by another one. 

Look at these real commits and try to imagine how you would read a tree full of
commits like these without feeling that the story is broken.

    commit 7f6bba884f8bf417d7ea25bb6ae106180cdcdbb2
    Author: developer <developer@boring.com>
    Date:   Tue Aug 9 12:06:19 2013 +0200

        actualizo la librería para conectarnos a gmail

        /vendors/gmail-api.py | 12 +++++++++---
        1 file changed, 9 insertions(+), 3 deletions(-)

    commit 9g6bba884f8bf417d7ea25bb6ae106180cdcdbd5
    Author: developer <developer@boring.com>
    Date:   Fri Aug 8 10:25:19 2013 +0200

        corrijo un error en la clase Person

        /classes/person.php | 12 +++++++-
        1 file changed, 7 insertions(+), 1 deletions(-) 
          


Poor Ego
--------



Fat Commits
-----------



