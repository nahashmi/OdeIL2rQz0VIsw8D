**Background**

This project analyses the customer feedback received by a logistics company on a survey that they did to a selected cohort of their customers. Based on the customers' answers to six questions about their satisfaction on the delivery of their order, their overall satisfaction is determined (happy or unhappy customer). 

**Solution**

This project builds a prediction model based on Machine Learning to predict whether the customer is happy or not based on the answers they give to the questions asked in the survey. 

After an exploratory data analysis (checking of missing/NULL values, outliers) and preparation of the data (test-train split), three classification models (Decision Tree, Random Forest, and XGBoost) were tried on the data with XGBoost giving the best prediction results. 

A 'Variable Importance' check was also performed to see if any of the six questions are more important than others when predicting customers' happiness.
