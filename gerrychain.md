---
layout: page
title: GerryChain 
---

### Gerrychain 

GerryChain uses Markov Chain Monte Carlo (MCMC) methods to help address some of the most challenging problems posed by redistricting. There are an enormous number of ways to partition the geography of a state into electoral districts that satisfy the basic legal requirements. As a point of comparison, there are at least as many valid congressional district maps as there are atoms in the universe. It is therefore impossible for human map drawers to consider the entire range of possible plans. The MCMC approach implemented by GerryChain is computationally efficient enough to generate hundreds of thousands of viable districting plans on a home laptop in a few hours. These large collections of plans are called ensembles.


GerryChain also allows users to track multiple attributes of interest for each individual plan in an ensemble, such as: population, demographics, and historical voting patterns by district. This enables users to conduct a variety of statistical tests and analyses to evaluate how proposed maps perform across several metrics of interest. For example, GerryChain has built-in functions to help users compute proposed metrics, like partisan bias, wasted votes, and the efficiency gap based on past election data. Because they contain so many plans, MCMC ensembles can converge to the underlying distribution’s various properties of all valid plans. These ensemble distributions can then be used as a representative baseline with which to compare the properties of specific proposed or enacted maps. Plans that are outliers on distributions of thoughtfully applied metrics can then be identified as potential cases of gerrymandering.

* [GerryChain Guide](http://www.math.wsu.edu/faculty/ddeford/GerryChain_Guide.pdf)
* [GerryChain Main Repo](http://github.com/mggg/gerrychain)


### Data and Methods

The primary form of data for analysis in GerryChain is a dual graph. Dual graphs are built using shapefiles containing geographic data that tracks the boundaries of voting precincts and tabular data that tracks population, demographic, and voting data within those precincts. For our state level case studies, we primarily used shapefiles that were constructed and made publicly available by the [Metrics Geometry and Gerrymandering Group (MGGG)](https://mggg.org/) at Tufts University. In the case of Colorado, we also merged in some archival election data from the Secretary of State's office. Because the 2020 Census data had not yet been released while we were conducting our analyses, we could not use the most updated population data. But in our guide we discuss some approaches to creating shapefiles from scratch after the census data becomes available on August 12, 2021. Other sources of pre-processed shapefiles can be found at the following:

* [MGGG](https://github.com/mggg-states/)
* [Redistricting Data Hub](https://redistrictingdatahub.com)
* [Open Precincts](https://openprecincts.org/)

