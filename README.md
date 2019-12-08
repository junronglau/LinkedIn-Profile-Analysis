# LinkedIn Profile Analysis
Submission entry for Hack Asia's Social Media Analytics Prediction 2019.

# Objective
The objective of the challenge is to analyze and gain insights from existing social media data and leverage on the data crawled to identify users who are likely to lease a car from our client, Daimler Fleet Management at different price points. 

# Motivation
We have selected Linked In as one of the platforms, as it is more likely that users upload real information to their profile. We obtained personal information about a profile such as their education, employment history and profile descriptions. From their education and job scope, we are able to deduce their rough spending power which is able to help us narrow down which tier of car leasing options are viable for them. In addition, their demographics and job scope can give insights as to which type of car within the viable leasing options would be suitable. 

# Insights
We extracted our top 10% of the profiles based on a set of scoring heuristics. The higher the score, the more likely they were of higher value to our client, Daimler Fleet Management. Our heuristics involved identifying 2 aspects of an individual: Spending power and Leasing propensity.  

<a href="https://ibb.co/3ctX5gB"><img src="https://i.ibb.co/NKwhgcZ/metrics.png" alt="metrics" border="0"></a>

Each measure is scored from a score of 0 to 1, and each measure in the defined heuristics (spending power and leasing propensity) is summed up and standardized to a score of 0 to 1. In other words, spending power will have a total score of one and leasing propensity will have a total score of one. Hence, the total score we can obtain here is a total of 2.

The results we obtained were that our high-value prospective customers were working for Prudential and ERA. Most also had up to 15 years of experience, which suggests that they are in their twenties to late thirties. Lastly, most of them are directors, founders or partners in their companies.

# Proposed solution
Based on our identified top profiles, we know that they are likely to go for sportier models due to their age. Hence, we propose marketing the newer S and E class models with a coupe or cabriolet variants. Also, we are able to target them in 2 ways.

1. Based on which companies the profiles belong to (ERA, Prudential), we can offer corporate rates and partnerships to attract their employees and managers to lease cars from Daimler. It may be beneficial to the companies since their agents/consultants may have a big need for a personal transport and can benefit from this partnership as well.

2. We are also able to link our identified profiles to Daimler's existing customer database. If they are already a customer, we are then able to see how much longer before their lease expires and offer them a personalized advertisement on which car to buy based on their LinkedIn profile analysis. If they are not on the existing customer database, we are still able to deploy a chatbot on LinkedIn to target these specific profiles, and recommend a suitable and personalized offering for them.
