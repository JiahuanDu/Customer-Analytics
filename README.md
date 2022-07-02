# Customer-Analytics

QUESTION 1: MODELING BINARY CHOICES

In this first question, you will work with a dataset simulated based on customer data of a skincare company located in US. This dataset contains weekly transaction data for a number of individual customers over a period between 2020 and 2021.
The skincare_data dataset consists of the following variables:
• ID: the id of the individual customer
• Week: the week number of the observation
• Year: the year of the observation
• Gender: the gender of the customer
• Age: the age of the customer
• Income: the total income of the customer on average per week (in USD)
• Deal: a dummy indicating whether the brand was on promotional deal in that week (1 = on deal, 0 = otherwise)
• Display: a dummy indicating whether there was an in-store display for the focal brand in that week (1 = present, 0 = absent)
• Coupon: a dummy indicating whether the customer received an online coupon from the focal brand in that week (1 = received a coupon, 0 = otherwise)
• Paid_Search_Advertising: how much the company spent on its paid search advertising per week (in USD)
• YouTube_Views: number of weekly views on its YouTube channel
• YouTube_Unique_Users: number of unique weekly users on its YouTube channel
• Facebook_Page_Views: number of unique weekly page views on Facebook from users logged into Facebook
• Facebook_New_Likes: number of new likes on the company’s Facebook page in that week 1
• Facebook_New_Unlikes: number of new unlikes on the company’s Facebook page in that week
• Facebook_New_Comments: number of weekly comments on the company’s Facebook page
• purchase: a dummy indicating whether the customer made a purchase in that week or not (1 = made a purchase, 0 = otherwise)

You are asked to do the following tasks:
1. Explore the data
Check descriptive statistics, outliers, missing/abnormal values, etc., and make plots/graphs if necessary.
2. Investigate the customer’s decision to purchase
2.a. Select your DV and choose your IVs
Create any extra IVs if you want. Explain clearly how these extra IVs are created/ operationalized.
2.b. Write a brief explanation/motivation for 3 IVs of your choice. What do you expect regarding the sign
of the effect (i.e., positive, negative, or both)? Formulate them as hypotheses. You can find examples of
hypothesis development in the journal articles that you were asked to read before our regular lectures.
• Find literature to support the development of at least one of these hypotheses.
2.c. Choose (an) appropriate method(s) and build your model(s)
2.d. Robustness check/Model validation
Show that your chosen model/method is better than other possible alternatives (if any). Normally this can
be done in three steps:
• Step 1: Split the original data into two parts: estimation and hold-out data sets.
• Step 2: Run your model(s) with the estimation data set and compute validation measures using the
hold-out data set.
• Step 3: Compare different models based on a set of validation measures and select the best one.
2.e. Estimate your selected model using the whole data set and discuss model fit statistics
2.f. Report findings, interpret the results, and formulate conclusions/discussions
2.g. Write a short part about managerial implications: Imagine that you are reporting these findings to the
management team of this company. How would they turn these insights into business actions?
2.h. If you had a chance to come back in time and collect more data, what kind of additional data you would
collect to improve the model? Explain why.


QUESTION 2: Choice-Based Conjoint Analysis

In this second question, you will work with a simulated data about the evaluation of alternative tablet specifications. A total of 250 people has participated in this choice experiment. You can access this simulated data through the “tablet_wide.RDS” file which is attached along with this document.  Each of these participants evaluated 5 different choice sets (tasks). In each task, participants needed to choose the best and the worst tablets among the three alternatives (i.e., stored in the selected and rejected columns respectively). The alternatives are different because of three attributes:
• Attribute 1: screen size with 3 levels, namely 9.7, 10.5, and 12.9 (inch)
• Attribute 2: storage capacity with 4 levels, namely 64, 128, 256, and 512 (GB)
• Attribute 3: price with 4 levels, namely 399, 599, 799, and 949 (USD)
The tablet_wide dataset consists of the following variables:
• resp_id: the id of the respondent
• set_id: the id of the set of choices, which always includes 3 alternatives
• screen_1: screen size of alternative 1
• storage_1: storage capacity of alternative 1
• price_1: price level of alternative 1
• screen_2: screen size of alternative 2
• storage_2: storage capacity of alternative 2
• price_2: price level of alternative 2
• screen_3: screen size of alternative 3
• storage_3: storage capacity of alternative 3
• price_3: price level of alternative 3
• selected: the best tablet selected by the respondent
• rejected: the worst tablet selected by the respondent
• age: age of the respondent
• gender: gender of the respondent

You are asked to do the following tasks:
1. Explore the data
2. Investigate the respondents’ preference for tablets 3
2.a. Select your DV and IVs
2.b. Choose (an) appropriate method(s) and build your model(s)
2.c. Model validation and comparisons
Show that your chosen model is better than other alternative model(s) (if any). For example, one relevant question you can answer in this part is should the effects of the attributes be linear/numeric or nominal?
See question 1 for the three general steps in model validation.
2.d. Estimate your selected model using the whole data set and discuss model fit statistics
2.e. Report findings, interpret the results, and formulate conclusions
For example, some relevant questions to be addressed:
• What is the most/least important factor (on average)?
• What would the ideal tablet look like?
