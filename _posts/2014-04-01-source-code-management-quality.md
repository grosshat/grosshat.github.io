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
management among developers.

---

Bad titles
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
