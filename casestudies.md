---
layout: page
title: Case Studies Overview
---

We conducted three different use cases of GerryChain across three different state contexts to demonstrate the process of computational redistricting. The purpose of this exercise is to illustrate the decision process associated with different types of analysis across differing state contexts. These case studies complement the guide's outline of GerryChain steps from start to finish, following the application of each stage alongside example code found on our [Github project repository](https://github.com/uwescience/dssg2021-redistricting).

### Case Study Structure

#### Stage 1. Data Wrangling:

The first step of any data driven project includes [data wrangling](https://online.hbs.edu/blog/post/data-wrangling). The specific steps required at this stage will vary based on the availability and current state of data for each individual state. In some cases, the shapefiles may be almost entirely ready for analysis. For others, users may have to spend some considerable time cleaning their requested files. 

We describe the data challenges specific to each state, particularly highlighting how a state-level focus and analyses unique to that context (e.g., political competitiveness, Voting Rights Act compliance) drive the front-end data work that allows the rest of the process to unfold smoothly .

#### Stage 2. Exploratory Data Analysis (EDA) & Modeling Decisions:

Before delving into the application of GerryChain, it is important to spend some time familiarizing yourself with state level data and the redistricting criteria unique to that context. Users will likely want to read their state’s legislation on the redistricting guidelines to help ensure that their approach in GerryChain conforms to those basic requirements; otherwise they risk producing maps that are not viable under the law. Relatedly, users should think carefully about what analyses they are interested in running and attempt to identify or develop the appropriate modeling decisions or tests for their metrics of interest. Careful consideration of these factors are important before the tools can be effectively applied.

We detail an EDA process for each state that's unique for GerryChain application. Specifically, we outline seven sequential steps that users should consider before applying GerryChain.

- Data Exploration
- Metric Selection 
- Seed / Starting Plan 
- Acceptance Functions
- Constraints
- Proposal Selection
- Number of Steps for Convergence

#### Stage 3. GerryChain:

The final step is actually running analyses of interest using the GerryChain library. The specific steps will depend heavily on your goals. If a user wishes to analyze an existing plan, GerryChain's built-in metric functions can provide information on commonly used redistricting measures such as Polsby-Popper scores and efficiency gap measures. If you want to explore the universe of possible maps for your state, GerryChain is capable of producing a large ensemble of plans that conform to state-level requirements. If you want to evaluate a proposed map, you can produce an ensemble that converges along a stable distribution so that you can compare existing plans to this distribution along a variety of metrics to determine whether or not proposed plans appear to be outliers.  

We developed three state case studies that work through each of these specific uses of GerryChain. In this way, we provide potential GerryChain users with a broad picture of what is possible using this powerful toolset. We endeavoured to document each process in detail to maximize transparency in what is oftentimes a complex, complicated, and technical space. 

### Use Cases

Georgia: Using GerryChain’s Built in Metrics
- Focus: Metrics 

Colorado: Using GerryChain to Support the Map Drawing Process
- Focus: Political Competitiveness

Texas: Using GerryChain to Evaluate Proposed or Enacted Maps
- Focus: Voting Rights Act and Opportunity Districts
