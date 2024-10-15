# Reliability Analysis Tool

This code is written in TypeScript using D3.js for data visualization. TypeScript is a typed superset of JavaScript, which helps catch potential errors at compile-time, making code more robust. D3.js is a popular JavaScript library for producing dynamic, interactive data visualizations in web browsers using SVG, HTML, and CSS.

## Purpose of the Code:
The code aims to estimate the parameters of a Weibull distribution and generate several plots based on the Weibull distribution's characteristics. The Weibull distribution is widely used in reliability engineering and failure analysis. This code offers the following functionalities:

Weibull Parameter Estimation (Maximum Likelihood Estimation - MLE):

The code estimates the shape and scale parameters of the Weibull distribution from given data using the Newton-Raphson method, a numerical optimization technique.
Probability Density Function (PDF) Plot:

This plot shows the probability density of failure times or the likelihood of an event occurring at a particular time. It's useful in understanding the distribution of failure times.
Survival Function Plot:

The survival function indicates the probability that a system will function without failure beyond a certain time. It is critical in reliability analysis.
Hazard Function Plot:

The hazard function describes the instantaneous failure rate at any given time, providing insights into whether the likelihood of failure increases or decreases over time.
Weibull Probability Plot:

A probability plot helps visualize if the given data fits a Weibull distribution. It plots the ordered data against theoretical Weibull quantiles.
## Visual Features:
D3.js is used to create smooth, interactive plots with axes, grid lines, tooltips, and legends.
Responsive SVG elements are used to dynamically adjust the plots to different screen sizes.
Interactivity is included in some plots to show tooltips with data details when hovering over points.
Intended Use:
This code is primarily intended for engineers and data analysts working with reliability data, failure analysis, and maintenance planning. It can be used to assess and visualize the reliability and failure characteristics of components or systems.
