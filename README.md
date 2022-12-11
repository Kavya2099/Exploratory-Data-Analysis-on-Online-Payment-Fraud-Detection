# Exploratory-Data-Analysis-on-Online-Payment-Fraud-Detection
Exploratory Data Analysis and Data Visualization on the Online Payment Fraud Detection using Python

With the increase of online payment now-a-days, the online payment fraud has also been rising and it's actually a major concern among the people who are not aware of the current technologies.

I've analyzed about the online payment fraud detection dataset taken from Kaggle and provided my insights.

- **Framework**- Jupyter Notebook
- **Language**- Python
- **Libraries**- Numpy, Panda
- **Plot Lib**- Seaborn, Matplot

Dataset - https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection/code?datasetId=2580326

# Analysis insights
### 1. What is the fraud percent that has happened in the overall transaction ?
Totally there is **8213** fraud transactions happened which constitutes around **0.13%** of total transactions happened
### 2. Under which type of transfer payment type fraud has occurred mostly.
Fraud has happened only in cashout and transfer type. **0.183 %** fraud happened in total cashout mode type and **0.769 %** fraud happened in total transfer mode type
### 3. Were we able to mark the fraud transaction as isFlaggedFraud?
No. Only **16** records of the 63 lakh records were flagged as fraud which is very less that constitutes to **0.195 %** of the total fraud transactions.
### 4. What is the percentage of incorrect flagged fraud records?
We have around 8197 records which are incorrectly flagged as 0 which constitutes **99.805 %** of total fraud records
### 5. Were all the isFlaggedFraud records that are marked as fraud is correct?
Yes. All the **16** transactions that are flagged as fraud is actually fraud transactions
### 6. At what amount range, fraud has happened?
The fraud amount transaction ranges between **1.3–3.6** lakh with most occurred in the range **340,000–360,000 (3.4–3.6 lakh)**.

# Conclusion
- We have large number of records which are incorrectly flagged as 0.
- Incorrect flagging might have big impact in future if we don't calculate it properly as it might lead to increase in online payment fraud percentage as people relay more on online payment nowadays.
- The amount range usually fraudsters target is aroung **1–4** lakhs which is certainly a large sum.
- Fraudsters focus during cashout and transfer mode type transfer.
- Fraud is less likely/rare to happen during payment mode transfer though people are using online payment more.
- There is not much information taken from **oldbalanceOrg,newbalanceOrig,nameDest,oldbalanceDest and newbalanceDest** columns though they had good positive correlation score

---------------------------------------------------------------------------------------------------

### You can also checkout my code here!

Kaggle - https://www.kaggle.com/code/kavya2099/online-payment-fraud-detection-eda

Medium - https://medium.com/@Kavya2099/online-payment-fraud-detection-exploratory-data-analysis-19ca87e0dc78

----------------------------------------------------------------------------------------------------
# References
- https://www.pluralsight.com/guides/cleaning-up-data-from-outliers
- https://analyticsvidhya.com/blog/2021/05/detecting-and-treating-outliers-treating-the-odd-one-out/
- https://www.analyticsvidhya.com/blog/2020/07/univariate-analysis-visualization-with-illustrations-in-python/
- https://jovian.ai/aakashns-6l3/us-accidents-analysis
- https://thinkingneuron.com/how-to-visualize-the-relationship-between-two-categorical-variables-in-python/
