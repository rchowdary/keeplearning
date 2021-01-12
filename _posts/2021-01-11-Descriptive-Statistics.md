---
toc: false
layout: post
description: Terminology for getting started with data EDA statistics.
categories: [statistics, python]
title: Data Exploration - Descriptive Statistics
---
# Descriptive Statistics

## Basic setup

It is always important to see how the data comes, what it looks like, and how it is saved etc.

One of the first steps is doing EDA (exploratory data analysis)

## Sampling

### Population and Sample

A population is the entire set of objects or events under study. It could be all the people or all the people in a state etc.

A sample is a representative subset that you have data on or of the objects or events under study. It is impossible to obtain/compute the entire population, so we always need sample.

Population is who/what you care about, and Sample is the data you collected.

From sample we try to extrapolate and come up with analysis on the population.

### Biases in samples

- Selection bias 

some records are more likely to be selected. 
For example if we are collecting a survey and ask an opinion only from people who wish to answer, then we are really collecting only subset that could lead to lot of bias. 

on a reviews site, we might have people who are passionate about the product and few people that have bad reviews, so to avoid selection bias we need to make sure both groups to be represented in our sample.

- Non response bias
Lot of times we send request for responses but we never get an answer back or who dont actually provide correct answers, all these fall into non response bias.

## Measurements on the Data:

### Sample mean

If we have quantitative variables, the first measurement is sample mean.
The mean of a set of n observations of a variable is denoted as $$\barx$$ and is defined as sum of all the observations by total number of observations (n).

Mean is essentially the centroid of the observations. The mean describes what a “typical” sample value looks like, or where is the “center” of the distribution of the data.

The mean is sensitive to extreme values (outliers).

Each time we collect a sample and calculate the mean it will vary so there is some uncertainity with mean.

### Sample median

The median of a set of n number of observations in a sample, ordered by value is the middle observation.
If length is odd, then the middle observation and if the length is even, average of the middle two observations or the 50th percentile.

The median also describes what a typical observation looks like, or where is the center of the distribution of the sample of observations.