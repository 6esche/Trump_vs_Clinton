# Trump vs. Clinton

For political campaigns it is very important to spend available funds efficiently. That's why campaigns focus on potential or undecided voters in constrast to all voters - comparable to market segmentation in companies. The project focuses on classifying voters of the 2016 election according to intention to vote and party preference.

Survey Data:\
Cooperative Congressional Election Study, 2016\
https://dataverse.harvard.edu/dataset.xhtml;jsessionid=6b5c02c5ffb8a8d919cea72c5eed?persistentId=doi%3A10.7910/DVN/GDF6Z0 \
Containing a pre- and a post-election wave\
Number of observations: more than 60.000, representative on national and state level\
Number of features: more than 550

Files:\
summary: presentation with the major outcomes\
master: overview of notebooks\
introduction: short insight into data and first try with random forest to see if data is suitable to answer the question\
cleaning: extensive data cleaning, labeling categorical variables, recoding filter questions, creating binary target variable (Trump - Clinton)\
eda: demografic data, opitions, etc. by candidate\
forest: prediction (Random Forest) if someone votes for Trump or for Clinton based on demografic data, perceptions and opinions\
forest_demo: prediction with the most important 8 variables and click-through-animation to find out if you would have voted for Trump or for Clinton
