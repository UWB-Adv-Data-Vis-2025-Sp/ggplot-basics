# ggplot-basics
Basic graphs in ggplot.

For this assignment, you will create graphs using ggplot by coding in R to build scatter plots!

Learning objectives:

- Be capable of running, modifying, and sharing scripts to accomplish analyze data and visualize in at least one scripting language.
- Manage project development to store, organize, and track code using digital collaboration tools for reproducibility.

## Preparation
Before beginning the assignment, read the following chapters from [Data Visualization](https://socviz.co/index.html#preface):

1. [Look at data](https://socviz.co/lookatdata.html#lookatdata)
2. [Get started](https://socviz.co/gettingstarted.html#gettingstarted)
3. [Make a plot](https://socviz.co/makeplot.html)

For this assignment, complete the task for each of the sections. You'll want to first make sure you have installed the required packages that are in the setup chunk. As you update your code to create ggplots, you can run individual chunks using the green play button in the upper right corner of the chunk. This helps you see the products of your code before knitting the full document.

Do not copy code from the book, rather try to write each line with the appropriate arguments. Keep in mind that ggplot builds each element of the visualization in layers.

## Task

Make an RMarkdown with your name as the author, that recreates the images and then knit it as an HTML file to upload it on Canvas as an attachment.

Recreate the following figures:

- Figure 3.13
- Figure 3.16

As you work on the figures, you can follow along with a previous tutorial for this chapter, but you this video doesn't cover git commits or submission for this assignment.

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/n4q6pcFSqy0/0.jpg)](http://www.youtube.com/watch?v=n4q6pcFSqy0)

As you complete each figure used to build the main visuals, write a commit message. 
There should be commits for the following states: 3.6, 3.7, 3.8, 3.9, 3.13, 3.14, 3.15, 3.16.

When you are finished, knit to Html, commit, push the code to GitHub and complete the assignment by submitting a pull request for feedback and paste the URL to the repo in Canvas. Once the URL us submitted, I will know it is safe to grade your work.

## Sections

### Name and date

Update the author's name and the date in the *YAML* section. 

### Set up

In your source chunk, you'll want to load the following packages.

```
if (!require("tidyverse")) install.packages("tidyverse")
if (!require("socviz")) install.packages("socviz")
if (!require("gapminder")) install.packages("gapminder")
```

If you are getting errors because these packages cannot be found, use the following codes in the console:

```
install.packages("tidyverse")
install.packages("socviz")
install.packages("gapminder")
```

### Figure 3.13

Here you will make your figure. You can write a commit for each figure or error leading up to the figure that matches. Be sure to include commits of the transitions and name the figures such as "Recreating Figure 3.4" and "Recreating Figure 3.7". Practicing frequent commits is a great habit.

### Figure 3.16
 
Here you will make your figure. Continue to write a commit for the figures or errors. 
