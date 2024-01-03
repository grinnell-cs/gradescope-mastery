Mastery Grading with Gradescope
===============================

This repository contains a variety of scripts and such for mastery grading using Gradescope. They tend to match the model used in Grinnell's CSC-151: Student grades are based primarily on the number of learning assessments and mini-projects that students complete.

We assume that learning assessments and mini-projects are named in such a way that it's easy to identify redos. Here are some examples.

* LA: Decomposition (Phase 1, Quiz 1)
* LA: Decomposition (Phase 1, SoLA 1)
* LA: Decomposition (Phase 1, SoLA 2)
* LA: Decomposition (Phase 1, SoLA 3)
* Mini-Project 1: Getting Started (Original)
* Mini-Project 1: Getting Started (Redo)
* Mini-Project 1: Getting Started (Second Redo)
* Mini-Project 1: Getting Started (Third Redo)

You can find instructions for the various scripts in their subdirectories. Here's a quick overview of the versions.

`gsm01-perl`
  : A Perl Script written by SamR. This version uses a configuration file
    (`gsmrc`) and also looks for tokens in a file called `tokens.txt`.
