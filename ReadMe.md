Text Analysis for Market Trend Prediction

Objective:
The objective of this project is to explore the potential of predicting market trends based on daily news headlines using machine learning techniques. The dataset spans eight years (2008-2016) and encompasses significant events such as the stock market meltdown, the Dodd-Frank Financial Overhaul, and the Occupy Wall Street movement.

Dataset:
The dataset used for this analysis is the Stock News Dataset available on Kaggle.

Project Structure:
This project is divided into several sections:

1. Text Analysis of News Headlines
->Identifying the top 100 most frequent words and bigrams in the news headlines, excluding stopwords.
->Analyzing these terms to understand their prevalence in the dataset.
->Creating word clouds for both single words and bigrams to visualize the findings.
->Discussion on the potential usefulness of frequently occurring terms as predictors of market trends.

2. Model Building - Predicting Today's Market
->Developing models to predict market movements ("up" or "down") based on the day's news 
  headlines using the top 100 words and bigrams identified earlier.
->Experimenting with at least two different models.
->Analysis of feature importance if using a model akin to Random Forest.
->Evaluating the performance of the models using metrics such as accuracy rate, confusion matrix, etc.

3. Reevaluation of Terms
->Reassessing the chosen terms if initial models do not perform satisfactorily.
->Comparing the top terms for days when the stock market increased (label=1) versus decreased (label=0).
->Adjusting the list of terms to eliminate potential noise and focusing on 100-200 words/bigrams with a 
  more significant correlation with market movements.
->Rebuilding prediction models with refined terms and assessing changes in performance.

4. Predicting Tomorrow's Market
->Modifying models to predict the next day's market movement.
->Aligning the dataset appropriately to account for the fact that news is published after the market has 
  closed.
->Ensuring correct alignment of data matrices (X and Y) by adjusting indices and potentially removing data 
  points as needed.

5. Extending Predictions
->Attempting to predict the market movement for the day after tomorrow.
->Evaluating the performance of models for this extended forecast and discussing any changes in prediction 
  accuracy.

6. Reflection and Insights
->Concluding the assignment by reflecting on the exercise.
->Discussing potential for overfitting, effectiveness of features tested, and any insights or conclusions 
  drawn from the analysis.

** Dataset included

Dataset Description :
Name :  Combined_News_DJIA.csv:
This ia a combined dataset with 27 columns.
The first column is "Date", the second is "Label", and the following ones are news headlines ranging from "Top1" to "Top25". 
