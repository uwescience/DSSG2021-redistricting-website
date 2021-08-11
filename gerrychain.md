---
layout: page
title: GerryChain 
---

### Gerrychain 

GerryChain is a Python library that uses Markov Chain Monte Carlo (MCMC) methods to help address some of the most challenging problems posed by redistricting. In every state there are an enormous number of ways in which the geographic space can be partitioned into electoral districts that meet the baseline constitutional criteria. As a point of comparison, there are at least as many valid congressional district maps as there are atoms in the universe. It is therefore impossible for human map drawers to consider the entire range of possible plans. GerryChain uses a computationally efficient approach that is capable of generating hundreds of thousands of viable plans on a home laptop in the span of a few hours. These large collections of possible plans are called ensembles.

GerryChain also allows users to track multiple data points of interest for each individual plan that is generated including population, demographics, and historical voting patterns by district. This in turn enables users to conduct a variety of statistical tests and analyses to evaluate how proposed maps perform across several metrics of interest. For example, GerryChain has built-in functions to help users compute proposed metrics, like partisan bias, wasted votes, and the efficiency gap based on past election data. Relatedly, by producing enough plans in an ensemble it is possible to reach a steady distribution, which can then be used as a baseline with which to compare proposed or enacted maps. Outliers on this distribution based on thoughtfully applied metrics can then be identified as potential cases of gerrymandering.

* [GerryChain Guide](http://www.math.wsu.edu/faculty/ddeford/GerryChain_Guide.pdf)
* [GerryChain Main Repo](http://github.com/mggg/gerrychain)


### Data and Methods

The primary form of data for analysis in GerryChain is a dual graph. Dual graphs are built using shapefiles containing geographic data that tracks the boundaries of voting precincts and tabular data that tracks population, demographic, and voting data within those precincts. For our state level case studies, we primarily used shapefiles that were constructed and made publicly available by the Metrics Geometry and Gerrymandering Group (MGGG) at Tufts University. In the case of Colorado, we also merged in some archival election data from the Secretary of State's office. Because the 2020 Census data had not yet been released while we were conducting our analyses, we could not use the most updated population data. But in our guide we discuss some approaches to creating shapefiles from scratch after the census data becomes available.


* [MGGG](https://github.com/mggg-states/)
* [Redistricting Data Hub](https://redistrictingdatahub.com)
* [VRA Ensembles](https://github.com/mggg/VRA_ensembles)
