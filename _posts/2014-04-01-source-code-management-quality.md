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
developers. Despite its importance, there is often a lack of taste for VCS
management among developers.


Bad titles
---
Too often the **commit moment** is understood, or at least felt, as a mere
formality. That means a tree full of bad titles and poor or just empty
descriptions, very hard to read later. Title and description should help to read
and search over the tree without the need of reading directly the code.

Look at these real examples and try to imagine how you would read a tree full of
commits like these without feelling you are reading a boring ass story.

` 
Update view.
`

`
Testing 1.
`


