# DataAnalytics-ConfusionMatrix

Exercise

The attached CSV file lists the customer, date, and dollar value of orders placed at a store in 2017. The actual gender and predicted gender of each customer is also provided.

Complete each of the following activities in a jupyter notebook or similar. Put your name and email at the top of the notebook and include your name in the notebook file name. Send back only your notebook file and please do not zip it.

A) Assemble a dataframe with one row per customer and the following columns:
    * customer_id
    * gender
    * most_recent_order_date
    * order_count (number of orders placed by this customer)
   Sort the dataframe by customer_id ascending and display the first 10 rows.

B) Plot the count of orders per week for the store.

C) Compute the mean order value for gender 0 and for gender 1. Do you think the difference is significant?

Ans: Based on gender, there is a slight difference in the behavior of order bought.

D) Assuming a single gender prediction was made for each customer, generate a confusion matrix for predicted gender. What does the confusion matrix tell you about the quality of the predictions?

Ans: Predicted the values as Positive and Negative and actual values as True and False. The accuracy comes out to be 0.64 from the confusion matrix.
