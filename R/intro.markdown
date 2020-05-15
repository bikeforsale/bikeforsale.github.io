---
layout: page
title: "Introductory R"
description: "Getting started in R"
header-img: "img/2x.JPG"
exclude_header: true
---

# Agenda

- Session 1: Wednesday, 15 March 2017, 15:00-17:00
- Session 2: Wednesday, 29 March 2017, 15:00-17:00
- Session 3: Wednesday, 12 April 2017, 15:00-17:00
- Session 4: Wednesday, 26 April 2017, 15:00-17:00
- Session 5: Wednesday, 10 May 2017, 15:00-17:00
- Session 6: Wednesday, 24 May 2017, 15:00-17:00
- Final exam: Friday, 26 May 2017, 15:00-17:00


# Course overview

## Objectives

The objective of this six-part course is to familiarize the student with the R software for data analysis. 

## Learning outcomes

By the end of the course, the student will be able to:

- Read into R data from different sources and file types (.csv, .xls, the web, .dta, .spss, etc.)  
- Explore data through both tabulations and visualizations  
- "Clean" and process data using a split-apply-transform framework (generate new variables, modify variables, filter)
- Understand some basic programming concepts
- Share data (publishing through the web, write datasets, etc.)
- Understand and be able to implement the concept of "reproducible research" in their analyses

## Prerequisites

Students are expected to have little or no experience with R. That said, students should have at least _some_ experience with data (ie, understand the concepts of variables, observations, etc.).



# Details


## Session 1: Setting up (90 minutes)

### Installation

- How to download and install R
- How to download and install RStudio
- How to install some useful packages

### Getting familiar with RStudio

- A fancy calculator
- How to talk to R
- How R talks to you
- Exploring objects
- Saving objects

### Customizing options

- Code color and syntax highlighting
- RStudio saving options

### Workflow

- Using projects
- How to organize data

### Writing some code

- First R program

## Session 2: Reading and exploring data (90 minutes)

### Reading data from "flat files"

- `.xls`, `.csv`, `.dat`, `.spss`, etc.

### Reading data from the web

- wunderground (weather data)
- github files
- google spreadsheets, etc.

### Using packages to get data

- `raster::getData`
- `fivethirtyeight`
- `Quandl`

### Weird R syntax: brackets, dollar signs, commas, etc.

- How to filter and subset
- Different ways to say the same thing
- Complex conditionals

## Session 3: Manipulating data (120 minutes)

### The split-apply-combine framework

- Why SAC is so useful
- How SAC can be implemented into your analyses

### Introduction to the `dplyr` package

- History and context
- How to use `dplyr` verbs:
    - the pipe: `%>%`
    - `mutate`
    - `summarise`
    - `group_by`
    - `arrange`
    - `filter`
    - `select`

### Writing data

- Saving an RData file
- Saving a csv

## Session 4: Visualizing data (120 minutes)

### The grammar of graphics by Edward Tufte

- Who is Edward Tufte and why does he matter?

### Introduction to the `ggplot2` package

- Histogram
- Density histogram
- Line chart
- Area chart
- Scatterplot
- Barplot
- Grouped barplots (stacked and dodged)
- Grouped scatterplots
- Faceted plots

## Session 5: Statistical analysis (120 minutes)

### Creating a linear model in R

- The `lm` function
- The `summary` function
- Using `broom::tidy` to clean up statistical outputs

### Creating a logistic regression model in R

- The `glm` function
- Understanding `log` and `exp`

#### Calculating odds ratios and confidence intervals

- The `confint` function

### Generating predictions

- The `predict` function

## Session 6: Reproducible research (90 minutes)

### Rmarkdown: Bundling analysis and writing

- Installing LaTeX
- How to create a basic Rmarkdown file
- How to use templates to create more complex Rmarkdown files

### Bibliographic management

- The DOI system
- Buidling `.bib` files for all papers
- Citing in-line and at end of paper
- Adapting paper for different citation paradigms



