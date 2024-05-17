The advertising industry heavily relies on understanding consumer behavior to optimize marketing strategies and maximize returns on investment. In this project, we aim to leverage machine learning techniques, specifically linear regression, to predict the area income of the user clicking on an advertisement based on various features in our advertising dataset.

**Dataset Source:** 

Our Advertising dataset consists of several key variables:

Daily Time Spent on Site: The amount of time a user spends on the website daily.
Age: The age of the user.
Area Income:  The target variable indicating the average income of the geographical area of the user.
Daily Internet Usage: The amount of time a user spends on the internet daily.
Ad Topic Line: The headline of the advertisement.
City: The city where the user is located.
Male: Binary variable indicating the gender of the user.
Country: The country where the user is located.
Timestamp: The timestamp of when the user clicked on the ad.
Clicked on Ad: Indicating whether the user clicked on the ad (1) or not (0).

We preprocessed the data, performed exploratory data analysis to understand the relationships between variables, trained a linear regression model, and evaluated its performance using relevant metrics.

Visualizations employed were Histograms, Joint plots, simple bar plots and kernel density estimation (KDE) plots.

**Data Splitting Method:**

The data was split into training and testing sets using an 80-20 split, where 80% of the data was used for training the model, and the remaining 20% was reserved for evaluating the model's performance. Stratified sampling was employed to ensure a balanced representation of ad clicks in both sets.





**Take Away from the Project:**

Through this project, I gained hands-on experience in building predictive models for ad click prediction using machine learning techniques.
I learned the importance of data preprocessing, feature selection, model evaluation, and visualization in developing effective predictive models.

In conclusion, our linear regression model demonstrates promising predictive capabilities in estimating the likelihood of a user clicking on an advertisement based on the provided features. Through thorough data analysis and model evaluation, we have gained valuable insights into the factors influencing ad clicks and predicting area income.


**Related Links**
Group's Google Colab notebook Link: https://colab.research.google.com/drive/1uZk_D6eeklc2Vzkvk-rcuDhJ3k1FBK25?usp=sharing

CSV files that are used in your code: https://drive.google.com/file/d/1G61iCHLoPszukOhMZkc4LPUbd8LfqIaR/view?usp=sharing
