This post will guide you through the basics of EDA, the essential first
step to understand your dataset and ask the right questions. EDA is a
process that depend on iteration. So you need to:

-   Generate questions about your data.

-   Start searching for answers by visualization, transformation, and
    modeling your data.

-   Use the knowledge you obtained to refine your questions and adjust
    your strategy to attack the problem with new questions.

Professor John Tukey (Tukey, 1977) strongly advocated the practice of
exploratory data analysis (EDA) as a critical part of the scientific
process.

“No catalog of techniques can convey a willingness to look for what can
be seen, whether or not anticipated. Yet this is at the heart of
exploratory data analysis. The graph paper and transparencies are there,
not as a technique, but rather as a recognition that the picture
examining eye is the best finder we have of the wholly unanticipated.”

## What would you find in this post?

EDA covers different techniques, in this article we will focus on
descriptive statistics and visualization and how we can apply those with
R.

Descriptive statistics include:

-   Mean - arithmetic average
    $$ \\bar{X}=
    \\frac{\\sum\_{i = 1}^{n}x_i}{n}
    $$
-   Median - middle value
-   Mode - most frequent value
-   Standard Deviation - variation around the mean
-   Interquartile Range - range encompasses 50% of the values
-   Kurtosis - peakedness of the data distribution
-   Skewness - symmetry of the data distribution

![](EDA_files/figure-markdown_github/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
