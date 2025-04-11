# ggplot-basics
Basic graphs in ggplot.

For this R assignment, you will create graphs using ggplot functions by coding in R! We will start with scatterplots by specifying two quantitative variables for the x- and y-axis. Before beginning, accept the assignment, pull your assignment repo from GitHub into RStudio using the New Project > Version Control, and then paste the appropriate URL. Considering that you face challenges when using your personal computer, you may complete the assignment with JupyterHub without tracking in Git with the expectation you ask for help to resolve the issues.

Learning objectives:

- Be capable of running, modifying, and sharing scripts to analyze data and visualize in at least one scripting language.
- Manage project development to store, organize, and track code using digital collaboration tools for reproducibility.
- Create an original data visualization using the grammar of graphic.

## Preparation

Before beginning the assignment, read the following chapters from [Data Visualization](https://socviz.co/index.html#preface):

1. [Look at data](https://socviz.co/lookatdata.html#lookatdata)
2. [Get started](https://socviz.co/gettingstarted.html#gettingstarted)
3. [Make a plot](https://socviz.co/makeplot.html)

For this assignment, complete the task for each of the sections. You'll want first to make sure you've installed the packages in the setup chunk. As you update your code to create ggplots, you can run individual chunks using the green play button in the upper right corner of the chunk. This helps you see the products of your code before knitting the full document.

Do not copy code from the book or instructions; try to write each line with the appropriate arguments. This way, you will know that ggplot builds each element of the visualization in layers.

## Task

Make an RMarkdown that recreates the images and then knit it as an HTML file to upload to Canvas as an attachment.

Replace the author's name.
Recreate the following figures:

- Figure 3.13
- Figure 3.16

As you work on the figures, you can follow along with a previous tutorial for this chapter, but this video doesn't include the git commits you should be completing. Be sure to submit this assignment as instructed below.

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/n4q6pcFSqy0/0.jpg)](http://www.youtube.com/watch?v=n4q6pcFSqy0)

Write a commit message as you complete each figure used to build the main visuals. 
There should be commits for the following states being made in Figure 3.13 chunk: 

- 3.6
- 3.7
- 3.8
- 3.9 
- 3.13

There should be commits for the following states being made in the Figure 3.16 chunk: 

- 3.14
- 3.15
- 3.16

When you are finished, knit to HTML, commit, push the code and the knitted file to your GitHub repo, and complete the assignment by pasting the URL to your the repo on Canvas assignment page. Once the URL is submitted, I will know it is safe to grade your work.

## Sections

### Name and date

Update the author's name and the date in the *YAML* section. 

### Set up

In your source chunk, you'll want to load the following packages using the *pacman* function p_load.

```
{r setup, include=FALSE}
pacman::p_load(tidyverse,nycflights13,gapminder,socviz)
```

If you are getting errors because these packages cannot be found, use the following codes in the *console*, not the script you:

Console:

- `install.packages("pacman")`

- `install.packages("tidyverse")`

- `install.packages("socviz")`

- `install.packages("gapminder")`

- `install.packages("shiny")`
```

### Figure 3.13

Here, you will make your figure. You can write a commit for each figure or error leading up to the figure that matches. Be sure to include commits of the transitions and name the figures, such as "Recreating Figure 3.4" and "Recreating Figure 3.7". Practicing frequent commits is a great habit.

### Figure 3.16
 
Here, you will make your figure. Continue to write a commit for the figures. 
