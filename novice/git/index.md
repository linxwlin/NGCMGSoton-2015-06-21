---
layout: page
title: Version Control with Git
---
> ## Learning Objectives {.objectives}
>
> *   Explain how version control is useful / essential

Wolfman and Dracula have been hired by Universal Missions
to investigate if it is possible to send their next planetary lander to Mars.
They want to be able to work on the plans at the same time,
but they have run into problems doing this in the past.

If they take turns,
each one will spend a lot of time waiting for the other to finish,
but if they work on their own copies and email changes back and forth
things will be lost, overwritten, or duplicated.

A colleague suggests using version control to manage their work.
Version control is better than mailing files back and forth because:

*   Nothing that is committed to version control is ever lost.
    This means it can be used like the "undo" feature in an editor,
    and since all old versions of files are saved
    it's always possible to go back in time to see exactly who wrote what on a particular day,
    or what version of a program was used to generate a particular set of results.
*   It keeps a record of who made what changes when,
    so that if people have questions later on,
    they know who to ask.
*   It's hard (but not impossible) to accidentally overlook or overwrite someone's changes:
    the version control system automatically notifies users
    whenever there's a conflict between one person's work and another's.

Version control is the lab notebook of the digital world:
it's what professionals use to keep track of what they've done
and to collaborate with other people.
Every large software development project relies on it,
and most programmers use it for their small jobs as well.
And it isn't just for software:
books (like this one),
papers,
small data sets,
and anything that changes over time or needs to be shared
can and should be stored in a version control system.

> ## Prerequisites {.prereq}
>
> In this lesson we use Git from the Bash Shell.
> Some previous experience with the shell is expected,
> *but isn't mandatory*.

## Topics

0.  [Introduction](index.html)
1.  [A Better Backup / Setting Up Git](01-setup.html)
2.  [Creating a Repository](02-create.html)
3.  [Tracking Changes](03-changes.html)
4.  [Exploring History](04-history.html)
5.  [Ignoring Things](05-ignore.html)
6.  [Collaborating](06-collab.html)
7.  [Conflicts](07-conflict.html)

## Other Resources

*   [Motivation](motivation.html)

[Next - Setting Up Git](01-setup.html)
