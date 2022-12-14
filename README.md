# (Prosper Loan Dataset)
## by (CHIBUIKE HENRY AZUBUIKE)


## Dataset

> The project was a loan dataset from ProsperLoans, and it consisted of 113,937 observations and 81 variables describing each observation, most of which existed as float data types and a bit of object and integer data types. some of these variables included occupation, debt to income ratio, original loan amount, borrower state, employment status, stated monthly income, credit scores of the borrowers, amongst many others.
I had certian features I wanted to explore, getting clarity on major reason(s) why people take loan, their categories or states, and major contributing factors that facilitate loans, so I had to drop off some columns that I thought were not of help to my investigation, then I took the average of the upper and lower credit scores and appended it to the new data frame in order to make analysis of the credit scores abit easier.


## Summary of Findings

> During the exploration phase, I had to transform some plot axes for more visibility and better analysis. I started off with the univariate exploration where I first explored the distribution pattern of the average credit scores, which revealed that the average creditscores appeared to be some what of a normal distribution with most data points centered around 650 to 750, but it is also a bit skewed to the left.
The distribution of loan applications over the years revealed that in the 4th quater of 2013 and the 1st quater of 2014, there were very high counts of loan application; generally, there were very high counts of loan application in the whole of 2013 and also in 2014.
Next, exploring the distribution of my main variable of interest: the 'ListingCategory (numeric)', revealed that the most reason why people took out loan was for the purpose of debt consolidation; and in this category, Califonia initially had the highest count, but further analysis revealed that the state with the highest debt consolidation ratio was South Dakota (SD) with 68% (surpassing Califonia with about 12%); which meant that the reason for Califonia having a high count initially was due to its massive population.

> For my bivariate exploration, I started by exploring relationship between the states and their debt consolidation ratio and I observed from my analysis and plots that 68% of persons from South Dakota took out loan for the purpose of Debt Consolidation, while in Iowa, the percentage of persons that took out loan for the purpose of debt consolidation was recorded to be 24%, which was the least amongst the other states.. More so, the bivariate exploration between income range and "debt to income ratio" of the borrowers revealed that persons that are within a higher income range tend to borrow way less than they earn; those earning lower tend to borrow a bit more in order to meet up (but not more than they earn); and then those who are unemployed tend to borrow for survival while earning little or nothing, and hence they have the highest "debt to income ratio". Finally, and the most interesting relationship in this section was exploring the "Debt consolidation ratio" and "Average credit scores" of the borrower states using a scatterplot, which revealed that there appeared to be some what of a direct relationship (with a strong correlation of about 80%) between the "Debt consolidation ratio" and "Average credit scores", which might be an indication that for the 'Borrower states', an increase in "Debt consolidation ratio" gives rise to an increase in "Average credit scores".

> In the multivariate section, A point plot was used to explore the relationship between average credit score, income range and employment status. It went on to reveal that those earning within the income range of 100K USD and above tend to have the highest average credit score, with the retired and 'not employed' topping that income range category. More so, a clustered plot above also reveals that those earning within the income range of 100K USD and above tend to have the least (and most favorable) 'debt to income ratio', and further analysis revealed that the retired persons in each employment category tend to have the least (and most favorable) 'debt to income ratio'.


## Key Insights for Presentation

> For the presentation, I focused on exploring the major reason why people took out loans, which turned out to be 'debt consolidation', then I went on to see the states that had the most percentage of this, and tried to explore a possible reason why by comparing with average credit scores.

> Next was the point that retired persons were more likely to get loans due to the fact that they usually tend to have a favorable 'debt to income ratio' and high credit scores.