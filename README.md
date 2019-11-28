# Coupon-Prediction
**The project is all about prediction of coupon redeemed by customers by doing feature engineering and EDA.**

1. There are several datasets containing different informations. The initial job was to extract all the important features and merge them with the training dataset and test dataset.
2. There were many relationships between tables like **campaign_data and train (or test), customer_demographics and train (or test), item data and customer_transaction, customer_demographics and customer_transaction** are all having **one-to-many relationships.** The other tables like **train (or test) and customer_transaction, coupons and item_data, coupons and customer_transaction** are all having **many-to-many relationships.** These tables are merged using different **Keys.**
3. **New features** are also being created by combining two or more features having common contribution towards the output which increases the efficiency.
4. Other **feature engineering** techniques are also being used like **Data Feature Formatting, filling NANs appropriately by grouping with other attributes and Label Encoding.**
5. Only **relevant features** are identified and used and relationships between multiple features are observed.
6. Cross-Validation using **Stratified K-Folds** is used along with **Grid Search** techniques.
7. **Random Forest Model** is used for classification of data points and parameters are optimized and tuned properly to give an accuracy of around **99.069%** which predicts the **Redemption Status** of the customers whether coupons is applicable on customers and which ones. 
