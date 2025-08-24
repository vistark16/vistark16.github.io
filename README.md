# Profile
Mathematics Bachelor Graduate at University of Indonesia. Passionate and high on curiosity and
enthusiast about processing data, analyzing data, and get useful insights. Highly motivated for self-
development and learning new experience. Self-motivated, responsible, easy to adapt, and caring for
the surroundings. Eager to learn and grow in the dynamic data analytics industry.

---

# Tech Stack  
- **Programming:** Python 3  
- **Data Analysis:** pandas, numpy, Google Spreadsheet  
- **Visualization:** matplotlib, seaborn  
- **Machine Learning:** scikit-learn, xgboost, imbalanced-learn (SMOTE)  
- **Database:** PostgreSQL  

---

# Previous Project
### 📑 Project Summary – Analysis of Performance Results of the Covolutional Neural Networ (CNN) Method in Pathological Myopia Classification  

#### Overview  
This project applies **Convolutional Neural Networks (CNN)**, specifically the **VGG16 architecture**, to classify **pathological myopia** from retinal fundus images. Pathological myopia is a severe eye disease that can lead to blindness, with a rising prevalence in Asia.  

---

#### Research Problem  
- How to apply CNN for classifying pathological myopia from fundus images.  
- How effective CNN (VGG16) performs in this classification task.  

---

#### Objectives  
1. Implement a CNN model with VGG16 architecture to classify pathological myopia.  
2. Analyze the model’s performance using evaluation metrics such as **accuracy, precision, and recall**.  

---

#### Methodology  
- **Dataset:** Ocular Disease Recognition (ODIR-5K) from Kaggle  
  - 600 normal images  
  - 454 pathological myopia images  
- **Preprocessing:**  
  - Resized to 224×224 pixels  
  - Data split into training, validation, and testing with 3 cases (70:30, 80:20, 90:10)  
- **Model:** CNN with **VGG16** architecture  
- **Training Setup:**  
  - Loss function: **Binary Cross-Entropy**  
  - Optimizer: **Adam**  
  - Epochs: **3**  
  - Batch size: **32**  
  - Learning rate: **0.001**  

---

#### Results  
- **Case 1 (70:30 split):**  
  - Accuracy **95.9%**, Precision **96.1%**, Recall **93.9%**  
- **Case 2 (80:20 split):**  
  - Accuracy **96.2%**, Precision **95.6%**, Recall **95.6%**  
- **Case 3 (90:10 split):**  
  - Accuracy **99.1%**, Precision **100%**, Recall **100%**  

✅ **Best Performance:** Case 3 with **99.1% accuracy, 100% precision, and 100% recall**  

---

#### Conclusion  
- CNN with **VGG16 architecture** is highly effective for classifying pathological myopia from fundus images.  
- The model achieved outstanding results, especially in Case 3, demonstrating its potential for supporting **early diagnosis and clinical decision-making**.  

---

#### Future Work  
- Explore modifications in **dense layers, activation functions, and dropout** to improve generalization.  
- Apply **advanced preprocessing techniques** for further accuracy gains.  

---






### 📊 Project Summary – Marketing Campaign Optimization  

#### Overview  
This project was conducted with the **Statstronauts team** to optimize digital marketing strategies using **predictive modeling**.  
The goal was to increase the **conversion rate** and improve campaign profitability.  

---

#### Business Problem  
- Limited customer data for targeting future campaigns.  
- Ineffective marketing strategies.  
- Low campaign success rate.  

---

#### Objectives  
1. Build a predictive model to classify customers likely to accept campaigns.  
2. Increase conversion rate and maximize profitability.  

---

#### Approach & Methodology  
- **EDA & Data Preprocessing**  
  - Removed missing values, outliers (Z-Score), and invalid data  
  - Feature engineering: *total products, total purchases, product variation, age*, etc.  
  - Class imbalance handled with **SMOTE oversampling**  

- **Modeling & Evaluation**  
  - Algorithms tested: Decision Tree, Random Forest, SVM, AdaBoost, XGBoost  
  - **Main metric:** Precision (to minimize false positives)  
  - **Best Model:** **XGBoost**, precision 85% with minimal train-test gap  

---

#### Results  
- Conversion Rate:  
  - **Before model:** 14.9%  
  - **After model (XGBoost):** 38.03%  
  - 📈 **Improvement:** +23.13%  

- Financial Impact:  
  - **Before model:** –$3,046 (loss)  
  - **After model:** +$697 (profit)  
  - 💰 **Improvement:** +$3,743  

- **Key Features:**  
  - Total Accepted Campaigns  
  - Recency  
  - Teenhome  
  - Education  
  - Marital Status  
  - Total Purchases  

---

#### Business Recommendations  
1. Prioritize customers who previously accepted campaigns.  
2. Develop promotions targeting newly married couples (without teenagers at home).  
3. Focus on customers with a **Graduation degree**, especially with **wine** products and **in-store purchases**.  

---

#### Conclusion  
The predictive model successfully increased conversion rates and improved financial outcomes.  
By applying **XGBoost** and data-driven targeting, marketing campaigns became more **effective and profitable**.  

---



