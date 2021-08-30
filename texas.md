---
layout: page
title: Texas
---

![image](https://user-images.githubusercontent.com/2799135/129251434-135ef164-32c9-43ee-bd97-4a92d3b3e3b8.png)


## Focus
Texas has experienced an estimated [15.9% population growth](https://www.texastribune.org/2021/08/12/texas-2020-census/) over the last decade, driven largely by Hispanic groups. This has resulted in two new congressional seats being allocated to Texas in the upcoming 2021 redistricting cycle. However, this growth has not been evenly distributed across the state. In fact, 143 of the 254 counties in Texas have experienced a declining population.

As Texas considers where to place these two new districts, it will be important to not only account for changing population patterns within the state, but also to ensure that minority groups have equal representation. In the new redistricting cycle, it is crucial to consider what a fair map looks like for Black and Latino voters. 

## State & Historical Context

Section II of the Voting Rights Act passed in 1965 prohibits states from practices that result in denying or abridging the right of US citizens to vote based on race or color. It goes on to say that a violation occurs if a political process (such as redistricting) results in unequal participation for specific race or ethnic groups. Thus, the VRA strictly prohibits members of a protected class from having less opportunity to participate in electing representatives of their choice. 

Texas in particular has a contentious history complying with the Voting Rights Act, and has faced several related court cases in the past decade.

| ![vra_tx](https://user-images.githubusercontent.com/2799135/129927714-3102b71e-9d22-4026-a40c-e1f04679cf61.png)| 
|:--:| 
| *Voting Rights Act Compliance in Texas*|


 
Section V of VRA required 16 states, including Texas to receive preclearance from the Department of Justice in order to change districting plans. During the previous cycle, the plan originally proposed by Texas state legislatures in 2011 was denied preclearance due to possible racial gerrymandering. But in 2013, the coverage clause of the preclearance requirement in the VRA was ruled unconstitutional by the Supreme Court. Thus, that proposed plan was signed into law by the Texas governor. 

The plan was challenged again in 2017 on grounds of racial discrimination, but it was ultimately upheld by the Supreme Court. This upcoming redistricting cycle will be the first where preclearance requirements are no longer in place, raising concerns for advocacy groups both in Texas and nationwide.

## Minority Effective Districts

To decide whether a plan complies with the Voting Rights Act, analysts can consider whether the districts that are being created are effective for minority groups to achieve fair representation. Researchers at the MGGG Redistricting Lab have designed a [method](https://mggg.org/vra) of quantifying this by considering a district to be effective if it is one where a minority _preferred_ candidate is able to both seek nomination during the primaries, as well as win the general election.

Using this methodology, we will examine the interplay of population shifts and minority representation considerations when analyzing the placement of the two new districts.


## Results


Using GerryChain, we are able to examine how plans incorporating the Voting Rights Act requirements compare to a base collection of plans that only considers population balance, contiguity, and county line preservation goals. As you can see in the two graphs below, if we add an additional constraint when designing plans that preferentially selects plans with more minority effective districts, we would be able to design plans that have 2 to 3 more minority effective districts on average based on the 2010 population data.

| ![vra_plan_comparison](https://user-images.githubusercontent.com/2799135/131414278-ffefe569-61c5-4ed5-bc3b-2563b4ea2a6f.png)| 
|:--:| 
| *Comparison of Proposed Plans Based on Criteria*|

With this in mind, if we now think ahead to the upcoming cycle and consider options for where the two new districts might go, it’s important for us to remember that the placement of these districts is crucial to fair representation. 

We can visualize the difference in the average number of districts per county when we compare potential plans from the previous redistricting cycle to proposed plans for the upcoming cycle. The green regions on the maps are areas where we’d expect to see a higher number of districts in 2021 than 2013, and the brown areas are counties where we’d expect to see a decrease in the number of districts. To take a deeper dive, we focused on the Dallas metro area and the Austin metro area, which are visualized below. If we only consider the population differences over the last decade, then on the top row, we can see green regions corresponding to areas that our analysis indicates could be likely candidates for adding a new district. However, if we build our 2021 ensemble of plans by prioritizing adding more minority effective districts, then the landscape of options changes. For example, when accounting only for population, Hays, Travis, and Bastrop counties are potential candidates for a new district. But if we want to maximize minority opportunity districts, then on the bottom row, we can see that Hays county is a much better option than Bastrop county. Similarly, it would be better to place a new district in select Dallas suburbs shaded in green in the second row if we want to better comply with the Voting Rights Act. 


| ![new_districts](https://user-images.githubusercontent.com/2799135/131414541-6898b2c1-a0d3-4aa0-b176-76aa8d0df54a.png)| 
|:--:| 


We hope that advocacy groups in Texas can use these methods and learnings to ensure that the map drawing process in Texas is fair and complies with the Voting Rights Act to the fullest extent.

Detailed code used for this analysis can be found on our [github repo](https://github.com/uwescience/dssg2021-redistricting), and the [User's Guide](https://uwescience.github.io/DSSG2021-redistricting-website/guide/) also provides a detailed walkthrough of the analysis decisions made at each step.
