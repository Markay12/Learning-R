# Welcome to Learning How to Code with R

## Introduction

This documentation is going to be heavily focused on learning how to use R for the purpose of Data Analysis.

Like Python, R is a powerful tool that can be used for data analysis.

## What is Data Science?

Data science is a discipline that allows the user to turn raw data into something that is understandable. It provides insight and knowledge to those who are viewing it.

Data science is a large field and uses math and figures to display new meanings to equations and life around us. The main methods that are used include

1. Importing Data
2. Tidying up the Methods
3. Transforming the Methods
4. Visualizing the Methods
5. Modeling the Methods
6. Communicating the Methods

The first thing you need to do is to import your data into R. This is done through a file, database or an API.

Secondly, you are going to need to tidy up your data. This means you store it in a consistent form that matches the semantics of the dataset. When data is tidy, each column is a variable and each row is an observation.

The common next steps are to transform, visualize and model the data. Transforming includes narrowing the observations of interest, creating new variables that are functions of existin variables and calculating a set of summary statistics. Visualizing the data shows you new things that you wouldn't expect and may raise new questions about the data. This may also show the person representing the data that something is wrong when everything does not line up. Models are complementary to visuals. Once you know the questions you are asking, you can use a model to answer your questions. Models are a mathematical and computational tool and scale well. The last step is communication, this is absolutely crucial to any data analysis projeect. You must be able to communicate your finidings to people that are going to be reading or viewing your models/data.

## Pre-requisites

These are the pre-requisites to help you learn from this site and to follow along.

There are four main things you are going to need.

1. R
2. R Studio
3. tidyverse (Explained Later)
4. Other Packages

### R

To download R, go to CRAN, the comprehensive R archive network. CRAN is composed of a set of mirror servers distributed around the world and is used to distribute R and R packages. Don’t try and pick a mirror that’s close to you: instead use the cloud mirror, https://cloud.r-project.org, which automatically figures it out for you.

### R Studio

RStudio is an integrated development environment, or IDE, for R programming. Download and install it from http://www.rstudio.com/download. RStudio is updated a couple of times a year. When a new version is available, RStudio will let you know. It’s a good idea to upgrade regularly so you can take advantage of the latest and greatest features. For this book, make sure you have at least RStudio 1.0.0.

### Tidyverse

You’ll also need to install some R packages. An R package is a collection of functions, data, and documentation that extends the capabilities of base R. Using packages is key to the successful use of R. The majority of the packages that you will learn in this book are part of the so-called tidyverse. The packages in the tidyverse share a common philosophy of data and R programming, and are designed to work together naturally.

You can install the complete tidyverse with a single line of code:

```R
install.packages("tidyverse")
```

### Other Packages

There are many other excellent packages that are not part of the tidyverse, because they solve problems in a different domain, or are designed with a different set of underlying principles. This doesn’t make them better or worse, just different. In other words, the complement to the tidyverse is not the messyverse, but many other universes of interrelated packages. As you tackle more data science projects with R, you’ll learn new packages and new ways of thinking about data.

Other three packages:

```R
install.packages(c("nycflights13", "gapminder", "Lahman"))
```
