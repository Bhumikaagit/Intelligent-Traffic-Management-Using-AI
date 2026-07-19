# Intelligent-Traffic-Management-Using-AI
Intelligent Traffic Management Using AI

# Description
This project presents an AI-based Intelligent Traffic Management System (ITMS) that 
predicts road traffic congestion levels (Low/Medium/High) using factors such as vehicle 
count, time of day, weather, and nearby events. Based on the prediction, it recommends 
traffic signal timing to help ease congestion at junctions.

# Features
 Exploratory Data Analysis (EDA) on traffic patterns
 Random Forest Classifier for congestion prediction
 Model evaluation using accuracy, confusion matrix, classification report
 Rule-based signal timing recommendation

# Tech Stack
 Python, Pandas, NumPy
 Scikit learn (Random Forest)
 Matplotlib, Seaborn

 # Graph 1: Distribution of Traffic Congestion Levels
   This graph shows the distribution of traffic congestion levels across the dataset. Most records fall under Low and Medium    congestion, while High congestion occurs less frequently, indicating a class imbalance. This visualization helps             understand realworld traffic patterns and highlights the need for balanced model training to accurately predict high         congestion scenarios.
   
   <img width="452" height="296" alt="image" src="https://github.com/user-attachments/assets/69718f36-ca67-4604-b78b-66cd6f1c63b3" />

 # Graph 2: Average Vehicle Count by Hour of Day

   This graph illustrates how vehicle traffic fluctuates throughout the day. Two distinct peaks are visible during morning      (8–10 AM) and evening (5–8 PM) hours, representing typical office rush periods. Traffic remains low during latenight and     early morning hours, confirming that time of day is a strong indicator of congestion and a key feature for the model.

   <img width="666" height="347" alt="image" src="https://github.com/user-attachments/assets/e753febc-2101-4fbd-a854-4824dfdb1662" />

 # Graph 3: Correlation Heatmap 

   This heatmap displays the correlation between numeric features in the dataset. Notably, vehicle count and average speed      show a strong negative correlation (-0.53), confirming that higher traffic volume reduces speed. Event nearby also           positively correlates with vehicle count (0.42), while day of week and weekend show strong correlation (0.79), helping       identify key relationships influencing congestion.

   <img width="464" height="371" alt="image" src="https://github.com/user-attachments/assets/2af50858-ab5a-422b-9004-58e66562f8e1" /> 

  # Graph 4: Confusion Matrix 

   The confusion matrix compares actual versus predicted congestion levels. The model performs strongly on Low (249 correct)    and Medium (227 correct) classes, but shows relatively weaker performance on the High class due to class imbalance in the    dataset (fewer high congestion samples). This highlights an area for future improvement, such as balancing the dataset or    applying class weighting techniques.

   <img width="439" height="362" alt="image" src="https://github.com/user-attachments/assets/17da1e4b-a70c-4f2b-8b9e-d9273971d0a3" /> 
  
  # Graph 5: Model Accuracy 

   This graph compares the model's accuracy on training and test data. The Random Forest Classifier achieved 91.96% training    accuracy and 81.67% test accuracy, showing a reasonable gap between the two. This confirms the model generalizes well to     unseen data without major overfitting, validating its reliability for real-world traffic congestion prediction.

<img width="508" height="365" alt="image" src="https://github.com/user-attachments/assets/c598e80e-007a-4329-8225-115599a6852f" />

# 
