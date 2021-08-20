---
layout: page
title: Georgia
---

<img src="https://ser-images.githubusercontent.com/83964372/129905764-6f9102d7-c061-404d-871e-57b7bc2e8840.gif" width="48%">

![GA](https://user-images.githubusercontent.com/83964372/129905764-6f9102d7-c061-404d-871e-57b7bc2e8840.gif)

<img src="https://ser-images.githubusercontent.com/83964372/129905764-6f9102d7-c061-404d-871e-57b7bc2e8840.gif" width="100%" height="100%"/>

<center><img src="{{ site.url }}{{ site.baseurl }}/assets/img/co_2012_dualgraph.png"></center>

<center><img src="https://user-images.githubusercontent.com/83964372/129905764-6f9102d7-c061-404d-871e-57b7bc2e8840.gif"></center>

<center><img src="{{ site.url }}{{ site.baseurl }}/assets/img/co_criteria.png" width="50%" height="50%"></center>

<center><img src="https://user-images.githubusercontent.com/83964372/129905764-6f9102d7-c061-404d-871e-57b7bc2e8840.gif" width="50%" height="50%"></center>


### Focus

In this case study, we’re going to focus on partisan considerations, as one of the many guidelines of the redistricting rules in Georgia; which also requires that state legislative districts be contiguous and the compactness of redistricting maps. Furthermore, the proposed map should also consider compactness and political subdivisions. Since state rules aim to achieve a total population that is substantially equal per district, the outcome of the election data in terms of the political parties involved is critical. The state of Georgia is composed of 14 districts with 58% under the control of the republican party, which raises questions concerning fair voting and voting statistics. The focus metric of this study is the "wasted votes" assessment on both the Republican and Democratic parties of the state to evaluate partisan outcomes.

### State Context

As we probe one of the built-in metrics of GerryChain, we introduce a standard which identifies some of the techniques of gerrymandering. Given that the state of Georgia has a history of single-party control, leads to a higher probability of partisan and racial gerrymandering. The redistricting process of Georgia should be closely monitored to ensure more competitive voting. Georgia has not received the kinds of state-level judicial relief concerning redistricting that has occurred in other states due to the ambiguity of the state’s constitution on voting rights and electoral districts. Accordingly, we use this case study with GerryChain to model ways for future users to be involved in the redistricting process of a state of interest facing similar challenges.

### Wasted Votes

Wasted votes by definition; are any votes cast for either party in excess to the 50% needed to win. The first step of our analysis involves generating an ensemble of proposed plans through GerryChain. Then, we measure the “wasted votes” count per district, per party, for each plan within the ensemble. Afterwards, we take the total “wasted votes” count along the ensemble to generate the percentages of “wasted votes” for either party. As such, we ultimately compare “wasted votes percentages with the 2011 enacted plan of Georgia using the 2016 presidential election data.

<img width="762" alt="Screen Shot 2021-08-18 at 10 32 03 AM" src="https://user-images.githubusercontent.com/83964372/129917504-9f2e117f-5fef-4db3-962e-e18be134a81e.png">

Considering this particular set of examples, which shows three possible redistricting plans for the same distribution of voters. Each box represent a voter, in which case the stars represent the A party voters and B party voters are shown as blank. Plan I, colored in red, shows a “competitive” and “fair” plan. So we end up with a proper distribution of votes among districts, with 3 districts favoring each party A and party B. Plan II, colored in green, shows “cracked” districts, with 5 districts favoring party A and 1 district favoring party B. As shown in Plan II, the 1 district which favors party B shows “wasted votes” in regards to the party, since A-voters are spread among several adjacent districts and B-voters are condensed into 1 district. Plan III, colored in blue, shows “packed” districts, with 3 districts favoring each party A and party B. In Plan III, both A and B parties show “wasted votes” since voters are condensed into their respective districts.

### Results

The first step of our analysis involves generating an ensemble of proposed plans through GerryChain (2000 plans). We then measure the “wasted votes” count per district per party for each plan within the ensemble. First, we take a state perspective by calculating the total “wasted votes” count along the ensemble to generate the percentages of “wasted votes” for each party. Afterwards, we evaluate “wasted votes” percentatges through a district perspective by averaging the “wasted votes” count for each district along the ensemble. As such, we ultimately compare the percentages of “wasted votes” along the ensemble with the 2011 enacted plan of Georgia using the 2016 presidential election data.

![dist_RD_plot_pres](https://user-images.githubusercontent.com/83964372/130162979-f576ed79-e058-4568-a2d5-998a0e5fb5ea.png)

Looking at the state, the total “wasted votes” percentages of the 2011 enacted plan of Georgia for both the Republican and Democratic parties reflects the history of single-party control on Georgia. The percentage of “wasted votes” for the Republican party was close to ~40%, whereas, the percentage of “wasted votes” for the democratic party was over ~60%. As for the ensemble of plans, however, we start to sample higher “wasted votes” percentages for the Republican party and lower “wasted votes” percentages for the democratic party as an indication that the ensemble of plans are sampling more fair voting outcomes. 

![dist_RD_dist_perc plot](https://user-images.githubusercontent.com/83964372/130164932-7628992f-6902-4cab-916f-00c93802856f.png)

Comparing the districts with the 2011 enacted plan of the state, we can clearly see that some districts are “packed” in regards to both the republican and the democratic parties.The percentage of “wasted votes”, however, are less pronounce for the Republican party once compared with the “wasted votes” of the democratic party. As for the ensemble of plans, however, the change in “wasted votes” percentages is less drastic as we go from district to district, which shows that the ensemble of plans are also reflecting more competitive voting outcomes per district. 

A curated reading list is provided below.

* Bernstein, M., Duchin., M., (2017). A Formula goes to court: partisan gerrymandering and the efficiency gap. *Notices of the American Mathemathecal Society, 64*(9), 1-6.  
* Deford, D., Dhamankar, N., Duchin, M., Gupta, V., McPike, M., Schoenbach, G., & Sim K. W., (2021). Implementing partisan symmetry: problems and paradoxes. *arXiv*, 1-20.

### Case Study Findings

Given the 2020 Census, the population of Georgia grew by 1 million since the 2010 Census, in which casse, Georgia now contains 10.7 million residents. During the summer, state lawmakers will hold 11 town hall meetings for public hearing about the redistricting process in Georgia, which occurs every 10 years. By Sept. 30, data regarding race counts, voting age, and housing occupancy status, will be release by the U.S. Census Bureau. By late fall this year (2021), the Georgia General Assembly will have a meeting to change the borders of the U.S House districts, state Senate, and state House.

### Resources

In addition, we have provided a [Github repository](https://github.com/uwescience/dssg2021-redistricting) which includes more details concerning data processing and analysis of this work. Interested parties involved in redistricting a state of interest with similar parameters are welcome to visit our Gerrychain User's Guide.
