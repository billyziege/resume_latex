# Table of Contents
1. [What is this repo?](#what-is-this-repo)
1. [Why do you have this repo?](#why-do-you-have-this-repo)
1. [How do I build your resume?](#how-do-i-build-your-resume)
1. [Can I steal this?](#can-i-steal-this)

# What is this repo

This repo houses my tex files and contents for building my resume using `pdflatex`.
For those uninitiated, L<sup>A</sup>T<sub>E</sub>X is an old school type-setting language
that came out of an even earlier typesetting language (TeX) that has now been
around for 40+ years.  It is widely used within academia largely due to its
ability to nicely typeset mathematical equations.  You can find more about 
[L<sup>A</sup>T<sub>E</sub>X here.](https://en.wikipedia.org/wiki/LaTeX)

In the repo, I created a page layout for my resume and some functions for creating
the content I have in the upper right side.
It's not a very big project, but it's also a one-page resume so it doesn't need to be.

# Why do you have this repo

What you need to know about me is that I don't really have much on github.
A lot of my current work is software engineering where I create internal documents.  I do this at work,
and it is not mine and cannot be shared.
When I am at home, I am mostly spending time with my family.  When I do have free-time to
do ``fun'' work, it's mathematics.  So when I apply to jobs, I need something to showcase some
of what I do.  This is why I have this repo publicly available.

# How do I build your resume

This depends on your OS.  I use fedora.  On fedora, I've installed pdflatex.
Some people use Overleaf for shared content, but I prefer to just use `git` to keep
tex files in a repository (like this one) and `pdflatex resume.txt` (in the tex folder)
to build because it is free and relatively easy.  If you search for "How do I install LaTeX?",
you'll probably find information on how to set it up for yourself.

# Can I steal this

Sure.  It's not really stealing.  The License I've attached is the Creative Commons license, which you can
read [here](LICENSE).  I find the License a little scary myself, but I don't really care what you do with this content. 
Feel free to copy, modify, and do what you like with the little that is here.

In fact, this is what I did for the four icon pngs in [`tex/images`](tex/images); I downloaded similar icons
from the [free-icons git repository](https://github.com/free-icons/free-icons/tree/master).  I took 7
of their svg icons, rotated the phone, changed the color on 5, and saved them as pngs, which are easier for `pdflatex`
to handle.
Note that they also have the
Creative Commons license although I would tell you to look at you they talk about their license as I do not represent
them, but I nevertheless want to give a shout out to that pretty insanely large repository for help in this project. 
