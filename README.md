The purpose of this analysis is to help banks manage their credit risk using the classification method. 
More specifically, with this script, we can predict which clients may default.

We have 2 Jupyter scripts and 1 Excel file. T
he check_data script is just for exploring the data. It helped me a lot in thinking about Feature Engineering. 
In the ML_Algo script, I performed my analysis.

Our target variable is 'loan_status,' which only takes two values: 0 (no default) and 1 (default). 
The issue is that the distribution of these values in the target variable is unbalanced, specifically with 0s being four times more frequent than 1s. 
In this case, our analysis is limited by certain algorithms, meaning we cannot use algorithms such as Logistic Regression, SVM, KNN, etc. 
However, I have prepared some models based on SVM and KNN to demonstrate the poor results as well.

As the final result, I can say that algorithms such as Random Forest, Decision Tree, and Gradient Boosting showed the best performance. 
Among them, I chose Random Forest for the prediction.

For Feature Engineering, I performed it twice. The second one was done at the end of the notebook. Unfortunately, I was not able to improve the results using the second Feature Engineering approach. 
You can try other methods, such as replacing missing values. I didn’t use this technique; instead, I simply removed them.

Feel free to use different Feature Engineering methods and Machine Learning algorithms. If you know of another method to improve the results, please share it with me. 
You can contact me with any questions related to this project. Here is my email address: nurlanakbarli@gmail.com or nurlanakbar13@gmail.com.

