# Kickstarting with Excel

## Overview of Project

### Purpose

This project is about learning to interpret data within a data set through functions, pivot charts, and graphs on Excel. The specific questions we wish to interpret from a large Kickstarter Funding Dataset provided are:

1.) The relationship between the launch month of a play project and its outcome

2.) The retlationship between the funding goal on Kickstarter for plays and its outcome


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater Outcomes based on Launch Date](https://github.com/namin1993/kickstarter-analysis/blob/f323c7a6ea50840adba86d9e97caf51bfbf20888/Resources/Theater_Outcomes_vs_Launch.png)

```
According to the **Theater Outcomes based on Launch Date** graph, there are several conclusions to draw from the data:
  - The most optimal date to launch a Kickstarter theater projects is around May. There is a greater range of successful fundraising campaigns to failed campaigns.

  - The worst month to launch a Kickstarter Theater projects is around December. There is almost a 50/50 chance the theater fundraising project will succeed or fail.
```

### Analysis of Outcomes Based on Goals

![Outcomes Vs. Goals](https://github.com/namin1993/kickstarter-analysis/blob/2600ef4f3f2cbe51654d2569abcde0d78c376fd1/Resources/Outcomes_vs_Goals.png)

```
According to the **Outcomes Vs. Goals** graph, there are several conclusions to draw from the data:
  - A Kickstarter funded Play will most likely succeeed if the funding goal is under $1000, ignoring currency conversion. 76% of all plays that cost under $1,000 for funding were successfully paid for. We are not taking campaign launch date into account for the success rate of a play being funded.

  - A play that costs over $45,000+ will not likely be funded.

  - No Play funding project has ever been canceled regardless of the amount requested.
```

### Challenges and Difficulties Encountered
```
One of the challenges I had with this project was using the COUNTIFS formula properly since I had to make sure the expression written used the correct reference values when I copy and pasted the formula for each Goal outcome. I couldn't think of a faster way to write out the contional statements within the COUNTIFS formula
```

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - The best month to launch a Kickstarter theater project is around May. The worst month to launch a theater project is in December.

- What can you conclude about the Outcomes based on Goals?
  - A Kickstarter funded Play will most likely succeeed if the funding goal is under $1000. Any play costing between $1000 to $4999 will also share a success rate close to a play costing less than $1000.

- What are some limitations of this dataset?
  - The dataset from the two graphs doesn't *exactly* connect the success rate of a Play project with the launch date of the project on Kickstarter. From the **Theater Outcomes based on Launch Date** graph, one cannot discern exactly the number of plays that are successful or unsuccessful on a certain month. The dataset also does not differentiate between the popularity of certain Parent categories according to each country.

- What are some other possible tables and/or graphs that we could create?
  - We could create a pivot chart similar to the **Theater Outcomes by Launch Date** pivot chart where it included Subcategory as a filter. We could also try to create a graph which depicted the success rate of certain project categories in certain countries.
