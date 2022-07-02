# Customer-Analytics

Choice-Based Conjoint Analysis

A total of 250 people has participated in this choice experiment. You can access this simulated data through the “tablet_wide.RDS” file which is attached along with this document.  Each of these participants evaluated 5 different choice sets (tasks). In each task, participants needed to choose the best and the worst tablets among the three alternatives (i.e., stored in the selected and rejected columns respectively). The alternatives are different because of three attributes:
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
