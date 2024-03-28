# Module20challenge
credit risk logisitics regression model




Overview of the Analysis


In this analysis, the purpose of the machine elarning models used are to determine whether a loan will be approved based off the loan applicants data. There are multiple columns of data including but not limited too loan_size,interest_rate,borrower_income,debt_to_income,num_of_accounts. In other words, we will be find relationships in the data set and try to predict whether or not the loan application will be approved. A 1 will indicate that it has been denied while a 0 indicates that it is approved. The finaical information we are using in our dataset is information about the cooresponding loan applicant's credit history.

In this paragraph, I will be detailing the procedure used in the machine learning process that I went through as part of this analysis. The first stage was too read in the data into training sets, so that we could run an analysis on the training sets. I created a new column name called loan status to capture the prediction of the loan being approved or not based off the finacial information. Next, I used a Linear regression model on the training data to fit the data. By generating a confusion matrix and classification report, I was able to determine the following. My logistic regression prediction model has an accuracy of 99 percent which makes it a great predictive model for the data set. The precision was approximately 85 percent, so out of all the instances predicted in class 1, 85 percent we're auctually true positives. The recall was 91 percent for class 1 which means the modle correctly identified 91 percent of them. 