# Google-Advanced-Analytics-Capstone
Google Advanced Data Analytics course capstone project - building a model to predict employee attrition

**About the company**

Salifort Motors is a fictional French-based alternative energy vehicle manufacturer. Its global workforce of over 100,000 employees research, design, construct, validate, and distribute electric, solar, algae, and hydrogen-based vehicles. Salifort’s end-to-end vertical integration model has made it a global leader at the intersection of alternative energy and automobiles.        

**Your business case**

As a data specialist working for Salifort Motors, you have received the results of a recent employee survey. The senior leadership team has tasked you with analyzing the data to come up with ideas for how to increase employee retention. To help with this, they would like you to design a model that predicts whether an employee will leave the company based on their  department, number of projects, average monthly hours, and any other data points you deem helpful. 

**Data Understanding**

The dataset contains 14999 entries ofemployee data from Salifort Motors. The data has 10 variables of experiential and operational employee data. 

**Modeling and Evaluation**

A logistic regression model was used to determine what employees would leave the company or not. The below chart is a confusion matrix for the model which shows a total of 504 misclassifcations and 2288 correct classifications. The overall model performed with a precision of 79%, recall of 82%, f1 score of .8, and 80% accuracy.

![cm](https://github.com/mastings/Google-Advanced-Analytics-Capstone/assets/22780966/95c0f84c-8d94-49df-81a8-5a20d83456c7)

**Conclusion**

It was found that the model is fairly accurate at predicting whether an employee will leave or not. Moving forward, I recommend that the company limit the total number of projects employees can work on and limit the number of hours worked. Also promote employees who have longer tenure. 
