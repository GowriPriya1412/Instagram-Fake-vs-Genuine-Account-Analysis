Instagram-Fake-vs-Genuine-Account-Analysis
This project focuses on identifying fake or spammer Instagram accounts using machine learning, data analytics, and interactive dashboards. It includes model building, feature analysis, and dashboard creation in Power BI.

Project Overview:
Instagram, like many social platforms, faces issues with fake and spam accounts. This project aims to classify accounts as fake or genuine based on various features like follower count, profile picture presence, and bio description.

Tools & Technologies Used:
 - Python (Pandas, Scikit-learn, Seaborn, Matplotlib)
 - Power BI (Dashboard creation)
 - SQL (Optional - data analysis)
 - Excel (Data cleaning and inspection)

Dataset:
Source: Publicly crawled Instagram data (March 2019)
Rows: 576
Target Variable: fake (1 = Fake, 0 = Genuine)
Key Features:
 - profile_pic
 - #followers, #follows, #posts
 - description length
 - name == username
 - nums/length username, fullname words

 Machine Learning Models:
 (i) Decision Tree Classifier
      - Accuracy: 87%
      - Easy to visualize and interpret.
(ii) Random Forest Classifier
      - Accuracy: 94.1%
      - High precision and recall
      - Feature importance used for interpretation.
