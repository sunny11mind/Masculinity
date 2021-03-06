# Masculinity

Data Science: What determines if a man will change his sexual behavior?
 
The point of this project was not simply to build and optimize a model that could tell us which men would a change their behavior.  This project was designed to also determine which factors were most influential in determining whether or not a man changed his behavior. Was it the man's level of concern that others see him as masculine, was it where he learned how to be a man, was it whether or not a man had witnessed sexual assault in their workplace. 
 
Logistic Regression: 
What's old is new again.

Logistic regression is one of the oldest and most powerful predictive algorithms. Its is used to describe data and explain relationships between independent variables and a binary dependent variable.  In this case, I was able to build a model to predict which men would change their behavior with a cross-validated score of 90% accuracy.  The features that were most associated with the predictions were able to determined from the resulting beta coefficients. 

Findings:
Of more than 1600 men 10 percent of them changed their behavior. Of the men who reported being exposed to #metoo, half of them changed their behavior. The most predictive factors from log reg was whether or not a person talked with a friend about whether they pushed a partner too far. The most predictive factor based on Adaboost was a man learning masculinity from his father.  In general, the overwhelming majority of men reported feeling very masculine or somewhat masculine. 

Future Work:
This project is still a work in progress. Demographic data included in the dataset (age, race, education, salary, etc.) has yet to be analyzed to determine their relationships with #metoo exposure levels or with which groups were more likely to change their behavior. I'd also like to to formally explore how different levels of masculinty behaved for example did their behavior change more or less across levels of masculinity). It should also be noted that less than one third of men responded to the question of whether or not they were familiar with #metoo. The imbalance noted in this feature will be addressed. F1 scores and error analysis are forthcoming. Check back soon for more!
