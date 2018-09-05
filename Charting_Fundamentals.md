# Box Plots
1. Also called a box-and-whisker plot.
2. is a method of showing aggregate statistics of various samples in a concise matter.
3. simultaneously shows the median of each value, the mininum and maximum of the samples,a nd interquartile range
** 4. useful for comparing distributions accross groups **
5. Five components `the median`, `two hinges, the upper and lower fourths (quertiles)`, `the data values adjacent to the upper and lower fences, which lie 1.5 times the inter-fourth range from the median, `two whiskers`, `out-liers` 

## Four Different Quarters of the Data
1. minimal value < x < first 25% of data (first quartile  
2. 25% < x < 50%
3. 50% < x < 75%
4. 75% < x < 100%

# Heatmaps
1. Visualizes three-dimensional data
2. The should be a continuous relationship between dimensions; using a heatmap for categorical data is totally wrong. 

# Animations
1. FuncAnimation

# Interactivity
1. interactivity depends of backend spport

## Pick Events
Allow you to respond when the user actually click on a visual element in the figure.

# Some Statistics

## Statistical Parameters

### Location Parameters
e.g. mean, median
1. shifts the locatin of a probability distribution

### Dispersion Parameters/ Scale Parameters
e.g. variance, standard diviation, interquartile range
1. strecthes or shrinks a probability distribution

### Shape Parameter
Any parameter that is neither a location parameter or a scale parameter

## Confidence Interval
>A type of interval estimate, computed from the statistics of the observed data, that might contain the true value of an unknown population parameter.
>the interval has a associated *confidence level* that, loosely speaking, quantifies the level of confidence that the parameter lies in the interval. More strictly speaking, the *confidence level* represents the frequence (i.e. the proportion) of possible confidence intervals that contain the treu value of the unknown population parameter.
[Confidence Interval](https://en.wikipedia.org/wiki/Confidence_interval)

## Sampling
### Population
The whole group that we are intersted in

### Census
A collection of data from the whole population

### Sample
A collection of data from part of the population
1. Random sample
2. Systematic sample
3. Stratified sample
4. Cluster sample

## Error Bars
### Definition
>Represent the uncertainty or variation of the corresponding coordinate of the point. 
>When standard deviation error bars overlap quite a bit, it's a clue that the *difference is not statistically significant*. 
>If error bars overlap even less, it's a clue that the *different is probably not statistically significant*.
> If error bars do not over lap, it's a clue that the *differnece may be significant*.
[Reference](https://www.biologyforlife.com/interpreting-error-bars.html)

### Types
#### Standard Deviation
How uch the values in each data group tend to deviate from thier mean.

#### Standard Error
Used when one wants to compare one mean to another.

It reports the varability i the means of data groups.

In normal distribution, SE = SD / sqrt(n)

#### Confidence intervals
1. Assumption on data distribution type is not needed.

2. If repeated samples were taken and the 95% confidence interval was computed for each sample, 95% of the intervals would contain the population mean.

3. 
