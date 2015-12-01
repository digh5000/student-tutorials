---
title: a template for student-written tool tutorials
authors:
- Jessie Raymond
date: 2015-08-12
reviewers:
- n/a
layout: default
---
#GitHub Visualizer
***
##Introduction

[Github Visualizer] (http://ghv.artzub.com/) is exactly that, a website that allows users to produce a visualization of github repositories. This site shows the scale of repositories and the amount of forks and pulls, and by who, have occurred within those repositories.
***
##Software & Setup

The visualizer is all in browser, so there is **no download**, or setup needed. Just load up the page and you're set!
***
##Terms

***
##Using the tool

To begin enter in any username from github at the top of the page under "GitHub username", press enter after entering the username. Making sure the "show" button is white instead of pale blue, click it to be shown a visualization of the user's repositories. For this tutorial I will be using [Freecodecamp] (https://github.com/FreeCodeCamp) as an example, which is an [open source community focusing on making coding education accessible](http://www.freecodecamp.com/) . 

Clicking show creates a simple visualization of that user's repositories as circles. 
The colour of the circles represents the **primary language**. Blue is Python, red is C, orange is R, green is Java etc

Hovering over the repositories shows the basic information about them, including the amount of forks and last time updated. 

You can select a repository by clicking on it's circle, or scrolling in the top bar in the second section. Click "Analyze" to view the individual repository. I'll be looking at the most popular repository which is also called [FreeCodeCamp](https://github.com/FreeCodeCamp/FreeCodeCamp).

This action overlays a graph on the repository visualization, but you can alter that by hovering over the navigation bar. 

In the individual repository view there's a timeline of changes to the files. Green data points indicate **additions**, while red points show **removals**. 
The orange dots represent **commits**. 
The bottom right corner has an index that allows you to see who is adding, deleting or modifying lines and files.

Clicking "Run" creates a video visualization of that data that maps the forks, and pulls chronologically, represented by coloured dots reflecting their primary lanugage, that move from one user icon to another.
***
##Conclusion

Now with a basic understanding of what data is present in the visualizer, you can use it to find mistakes, or just see how data has fared since its creation. 
Having all that information in a concentrated area, and colour coded makes it easier to digest. 
Enjoy!
