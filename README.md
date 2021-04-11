# thebrazilianshackathon

Predicting the use of Destructive Illicit Substances

Introduction

Our team was intrigued by the DAST-10 questions provided and formulated the question: can we predict the likelihood of an individual engaging in destructive activities through drug use. 
Methodology


Firstly, we devised a metric based on the answers of each DAST-10 question which determines how intensely an individual has engaged in destructive activities. We looked at the series of illicit substances and devised which of these drugs are highly correlated with the DAST-10 answers. We can use a random decision forest to help us determine, when running an ML algorithm, which feature will have the highest correlation with our destructiveness metric to determine which drugs have the most negative impact.


Once we identify which drugs are the most vital we locate these users geographically and identify which US state has the highest percentage of people who take these substances to roughly identify where the problem is localised. We then look at the relationships between gender, income, and age and these substances to build a logistic regression model to answer our original question and determine whether someone, given their demographics, will not only be addicted to this substance but also engage in destructive activities related to drug use.
