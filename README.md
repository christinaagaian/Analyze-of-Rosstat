# About my first project on GitHub 'Analyze-of-Rosstat'
#####
# Null Hypothesis:
###
# I hypothesize that the most popular major sources of income have not changed over the decade, but their popularity among different age groups has changed.
#####
# Rationale for file selection:
###
# I am going to investigate the variability of the main way of earnings of the population in Russia, for this purpose I have chosen the data in the census of the population on the main source of livelihood on the income of the population for 2010 and 2020. I am interested to find out how the way of earning citizens, distributed by age categories, has changed in 2020 compared to the picture of 2010, and that's why I chose these files.
# The rationale for choosing this type of dictionary:
# I have collected data from each table into 4 dictionaries:
# In the dictionaries d_ev_2010, d_ev_2020 for 2010 and 2020, respectively, the key is the name of the types of income, types of income, and the values are dictionaries in which the keys will be the categories of the population (by age), and the values are the number of people in this category receiving this income. I chose this dictionary structure because it shows how many people of certain age groups earn in the way indicated as the key
# In addition, we also used the dictionaries d_total_2010, d_total_2020 for 2010 and 2020, respectively, where the keys were the types of income, and the values were the total number of people who use this financial instrument to earn money. I used this dictionary structure because, as part of our research, we wanted to find out how much the approaches to earning among the population have changed over the past 10 years years , regardless of age, in connection with new trends (for example, the concept of “lifelong education” arose, the ideas of passive income spread).
# In the course of our research, I calculated the following descriptive statistics:
# ● the average number of people with a certain source of income
# ● Median age for each source of income (as well
as lower and upper quartiles, lower and upper bounds,
uncharacteristic values)
# ● mathematical expectation of age for each source
of income
# ● Spearman's correlation between age and type of income
# ● the most popular and unpopular main source of income
#####
# Interpreting the average value for each source of income:
###
# Interpreting the results by the average, consider the indicators that have changed a lot:
# 1) The average number of people who receive a scholarship has increased significantly (approximately 3.5 times). Most likely, this is due to the fact that there is a trend towards lifelong education. The cases when people go to get higher education, being over 20 years old, have increased significantly. This is due to the fact that the concept of “ self-development” has become fashionable, which implies learning something new on a regular basis.
# 2) The average number of people who receive income from renting or leasing property, patents and copyrights has increased critically (approximately 3.5 times). This can be attributed to the fact that the modern solvent generation has stopped demonizing creative professions and startups, and has also become more educated in the field of financial literacy, since a contribution to property is a good financial instrument that helps save money from rising inflation. In addition, the legislation created more favorable conditions protecting both sides of the lease agreement, which made it more profitable, which means that the number of white schemes has increased.
# 3) The average number of people receiving income from pensions, benefits and other payments from organizations and the state has increased (by about 1 million people), which is most likely due to the aging trend of the Russian population and, accordingly, an increase in the number of people receiving pensions and not being able to work.
# 4) The average number of people receiving income from savings, dividends, and interest has doubled, which may be due to a rapid increase in inflation and an increase in financial literacy among the population
#####
# Interpretation of mathematical expectations and medians
###
# I will interpret these indicators in conjunction, since the medians check the correctness of the mathematical expectation. (it is worth noting that the median has not changed in any way, unlike the mathematical expectation. However, due to other indicators such as quartiles and uncharacteristic values, we understand that the mathematical expectation is determined correctly) According to the changes in mathematical expectation, we can conclude:
# 1) That the expected age of a personal subsidiary farm has increased (from 40.74 in 2010 to 49.65 in 2020), for the reasons mentioned earlier
# 2) The expected age of people who receive income from savings, dividends, and interest has increased (from 39.5 in 2010 to 47.09 in 2020). This happened because the inflation rate increased between 2010 and 2020, and people began to think more about how to safely save money from inflation.
#####
# Interpretation of the Spearman correlation
###
# We chose it because this correlation indicator is stable. Speaking about Spearman's correlation between age and type of income, we can note the following:
# 1) The correlation for the personal subsidiary farm has changed (it was negative, it became positive). We believe that this is due to an increase in life expectancy (previously, a smaller percentage of people lived to retirement, at which point people begin to lead such a lifestyle). In addition, the experience of covid-19 probably played a role in changing Spearman's correlation, since many pensioners moved to dachas during that period, where they were able to discover a new type of earnings
# 2) The correlation for the scholarship has changed (it has decreased in terms of inverse proportionality, that is, more senior people have started/continued to receive higher education and receive income from the scholarship). We believe that this is due to the above-mentioned trend of continuing education.
# 3) The correlation for savings, dividends, and interest has changed (it was negative, became positive). We believe that this is due to the fact that the older generation, who tend to keep their funds in gold/real estate, began to fight inflation by creating assets.
#####
# Interpretation of the minimum and maximum source of income:
###
# Interpreting the results for the most popular and unpopular main sources of income, the following conclusions can be drawn: The most popular type of income has not changed, while the most unpopular, instead of renting or leasing property, patents and copyrights, was earning on something else not listed in the tables. This happened for the same reasons as the increase in the average number of people who receive income from renting or renting property, patents and copyrights. Hence, he stopped being unpopular and was replaced by another one.
#####
# Interpretation of the rating:
###
As we assumed in the null hypothesis, the most popular sources of income have not changed much over the decade: wages still occupy the leading place, only dependents and pensions have changed places (dependents have gone down to third place, and pensions, on the contrary, have risen in the ranking). This trend is explained by the following: despite government programs, the country still has a low birth rate and an “aging" population. Thus, the number of elderly people has increased (as well as the main source of their earnings – pensions), and the number of children is not growing fast enough and cannot align with the high level “aging" (therefore, dependency as the main source of income for minors has given way to pensions in the ranking).
