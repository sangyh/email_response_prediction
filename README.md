# Prediction of Engagement to Sales Emails
Prediction of engagement (opening, replying) with sales emails by recipients based on email content, time of sending, role etc.

Description
Sales personnel send out thousands of emails any given week, and optimizing any of the several factors to increase response rate can be hugely beneficial.  The factors include delivery time, day, prospect details, prospect's company, type of engagement etc. Engagement can either be ignoring the email (failure) or opening email, clicking on a link or even responding (varying levels of success). 

So, using a real-world dataset (tabular, 1M rows, 44 columns), I modeled the prospect behavior as a binary classification task (ignored or not ignored). The f1-score was 0.69. 
The challenges and key requirements with this project were tackling class imbalance, need for interpretability, rapid prototyping (~5 days) and delivering actionable insights. 
The result recommended ideal combinations of email body and subject length, time of delivery and showed the power of repeated attempts to reach out to the prospect, and identified people who were more likely to buy the product enabling prioritization.
