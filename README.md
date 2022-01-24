# ggplot-basics
Basic graphs in ggplot.

For this assignment you will complete code to build commonly encountered plots including scatter plots, facets, column plots, and box plots.

Before beginning the assignment, read the following chapters from https://r4ds.had.co.nz/index.html:

0. Welcome
1. [Introduction](https://r4ds.had.co.nz/introduction.html)
2. [Explore: Introduction](https://r4ds.had.co.nz/explore-intro.html)
3. [Explore: Data visualization](https://r4ds.had.co.nz/data-visualisation.html)

If this is your first time working with R code or need some extra help recalling how it works, I recommend using the following materials:

- Get Started from [Data Visualization](https://socviz.co/gettingstarted.html#gettingstarted) by Healy 
- [learnr](https://rstudio.github.io/learnr/index.html): an r studio package that shows some of the basics of working with R and R studio. 

For this assignment, complete the task for the below sections. You'll want to first make sure you have installed the required packages that are in the setup chunk. As you update your code to create ggplots, you can run individual chunks using the green play button in the upper right corner of the chunk. This helps you see the products of your code before knitting the full document.

Do not copy code from the book, rather try to write each line with the appropriate arguments. Keep in mind that ggplot builds each element of the visualization in layers. 

As you complete each section, write a commit message. When you are finish, knit to html, commit, push the code to github and complete the assignment by submitting a pull request.

### Name and date

Update the author name and the date in the *YAML* section. 

### Scatter plot and aesthetics
 
For this first plot of miles per gallon (mpg), use aesthetic mappings to create a scatter plot like those shown in [section 3.3](https://r4ds.had.co.nz/data-visualisation.html#aesthetic-mappings) and [3.6](https://r4ds.had.co.nz/data-visualisation.html#geometric-objects). Modify the code in the *scatter plot* chunk. 

Note that there are two `aes()` functions that should contain arguments for assigning aesthetics as follows: 

- the x-axis for the engine size and y-axis for the miles per gallon on the highway in the `ggplot()` function.
- the color of vehicles by class in `geom_point()` function.

The last argument is the `geom_smooth()` which should make the trend line, a single blue curvy line with gray margins of errors of the overall pattern in the data.

### Facets of a scatter plot

Modify the *faceted scatter plot* chunk to show the trend across the two different years shown in the data. 
To do this, copy your working code and then add a new function such as `facet_grid()` or `facet_wrap()` as shown in [section 3.5]( https://r4ds.had.co.nz/data-visualisation.html#facets)

### Bar plots

Next read [sections 3.7](https://r4ds.had.co.nz/data-visualisation.html#statistical-transformations) and [3.8](https://r4ds.had.co.nz/data-visualisation.html#position-adjustments) and use the `position` argument of the `geom_bar()` function to modify the current graph in the *bar plot* chunk into either a stacked bar graph with `fill` or a distribution bar graph with `dodge`.


### Box and whisker plots

Next read [section 3.9](https://r4ds.had.co.nz/data-visualisation.html#coordinate-systems) to create a box and whisker plot in the *box plot* chunk that shows the median and standard distribution for the distribution of miles per gallon on a highway for each different class of vehicle. Use the `fill` argument to display the different classes. Your plot should be horizontal rather than vertical and you can do this using the `coor_flip()`.
