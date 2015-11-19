---
title: Static flow
description: null
author: Danny Chapman
layout: post
category: past
tags: 
  - Open Data
  - Design
  - Workflow
published: true
---


This week, I was lucky enough to moderate a panel at SXSW Interactive on static website design. Great discussion was had from a variety of points of view — coder, designer, project manager. What really stood out from our conversation, and from the great questions from the audience, was that was this isn't really about tools - it is about workflow. How going from a larger CMS, or software driven process to something more nimble can effect positive change in every part
of the website production process.

[Apple](http://apple.com)

### Process

What’s interesting in reverting to static files is just that - the files. By representing website content in a file, and not somewhere in a database, how you interact with that file can change.

To be clear, I think it’s important to not conflate git and GitHub when it comes to static site generation. If you’re using GitHub pages and Jekyll, then git is indeed baked in. But, a static site does not by definition mean you’re using git. What it does mean, is you now have a physical file, that lives *somewhere*, rather than a database. That makes things interesting, and generally speaking, much more flexible. A simple markdown file can be edited offline, in text editor, online is a SAAS product, or managed directly in a version controlled flow of your choice — git, or otherwise.

### Structured Content

As Jessica Teal mentioned on our panel, putting content in Markdown essentially takes the WYSIWYG editor out of the content creation process. This is a good thing, usually resulting in much cleaner, well structured content.

### Design

Segregating well-structured content from design assets makes for a much better workflow, and ultimately, more consistent design. It’s much harder to muddy the waters between the two, when all a well-structured markdown file can do each time, is load the same exact template file. No more bold, italic red text - a nightmare any designer who has worked with a CMS knows all too well.


### Learn More

To learn more, be sure to [check our slide deck](http://ben.balter.com/the-dynamic-site-is-dead).
