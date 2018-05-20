# Web-Scraping-for-Indeed.com-and-Predicting-Salaries
In this project, I will practice two major skills: collecting data by scraping a website and then building a binary predictor with Logistic Regression.

I am going to collect salary information on data science jobs in a variety of markets. Then using the location, title and summary of the job I will attempt to predict the salary of the job. For job posting sites, this would be extraordinarily useful. While most listings DO NOT come with salary information (as you will see in this exercise), being able to extrapolate or predict the expected salaries from other listings can help guide negotiations.

Normally, I could use regression for this task; however, I will convert this problem into classification and use Logistic Regression or any other suitable classifier.

- Question: Why would I want this to be a classification problem?
- Answer: While more precision may be better, there is a fair amount of natural variance in job salaries - predicting a range may be useful.

Therefore, the first part of the assignment will be focused on scraping Indeed.com. In the second, I'll focus on using listings with salary information to build a model and predict additional salaries.
