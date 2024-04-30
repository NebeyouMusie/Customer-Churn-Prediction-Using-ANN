# Customer Churn Prediction Using ANN
- Customer churn prediction is used to measure why customers are leaving a business.
- We will build a deep learning model to predict the churn and use precision,recall, f1-score to measure performance of our model

## What is its usecase?
 - Customer churn prediction is a valuable tool for businesses that rely on recurring revenue or subscriptions. By identifying customers who are at risk of churning (cancelling their subscription or service), businesses can take proactive steps to retain them. This can lead to significant cost savings, as it's generally cheaper to retain an existing customer than acquire a new one.
 - Here are some specific use cases for customer churn prediction:
    - **Targeted marketing campaigns**: By knowing which customers are at risk of churning, businesses can target them with specific marketing campaigns designed to win them back. These campaigns could offer discounts, exclusive deals, or other incentives to stay.
    - **Improved customer service**: Customer churn prediction can also help businesses identify customers who are having problems or are dissatisfied with the service. By proactively reaching out to these customers and addressing their concerns, businesses can improve their customer satisfaction and reduce churn.
    - **Product development**: Customer churn prediction can also be used to identify areas where a product or service can be improved. By analyzing the factors that contribute to churn, businesses can identify areas where they need to focus their product development efforts.
 - Overall, customer churn prediction is a powerful tool that can help businesses improve customer retention, boost revenue, and gain a competitive edge.

## Data Description
 - I have used the `customer-churn.csv` file for the project
 - The dataset contains information like:
  1. gender            
  2. SeniorCitize  
  3. Partner           
  4. Dependents        
  5. tenure        
  6. PhoneService      
  7. MultipleLines     
  8. InternetService   
  9. OnlineSecurity    
  10. OnlineBackup      
  11. DeviceProtection  
  12. TechSupport       
  13. StreamingTV       
  14. StreamingMovies   
  15. Contract          
  16. PaperlessBilling  
  17. PaymentMethod     
  18. MonthlyCharges 
  19. TotalCharges 
  20. Churn


## Libraries Used
 - Numpy
 - Pandas
 - Matplotlib
 - Seaborn
 - Scikit-learn
 - TensorFlow
 - Keras
 - imbalanced-learn

## Evaluation Metrics for the Imbalanced Data
 - Accuracy: 0.77  (77%)
 - Precision for class '0': 0.81 (81%)
 - Precision for class '1': 0.58 (58%)
 - Recall for class '0': 0.88 (88%)
 - Recall for class '1': 0.45 (45%)
 - f1-score for class '0': 0.85 (85%)
 - f1-score for class '1': 0.50 (50%)

## Solution used to solve the metrics due to the imbalanced dataset
 - We'll try to solve the problem using 4 Methods
 1. Undersampling
 2. Oversampling
 3. SMOTE (Synthetic Minority Oversampling Technique)
 4. Ensemble with undersampling

## Installation
 1. Prerequisites
    - Git
    - Command line familiarity
 2. Clone the Repository: `git clone https://github.com/NebeyouMusie/Customer-Churn-Prediction-Using-ANN.git`
 3. Create and Activate Virtual Environment (Recommended)
    - `python -m venv venv`
    - `source venv/bin/activate`
 4. Install Libraries: `pip install numpy pandas matplotlib seaborn scikit-learn tensorflow imbalanced-learn`
 5. Open `customer-churn.ipynb` and run all cells
 6. Or you can download the `customer-churn.csv` and `customer-churn.ipynb` file from the repository, upload those files to [Google Colab](https://colab.research.google.com/) then run all the cells in the `customer-churn.ipynb` Notebook

## Acknowledgments
 - I would like to thank [codebasics](https://youtube.com/@codebasics?si=S9xKOK9Hztsu2-Oi)

## Contact
 - LinkedIn: [Nebeyou Musie](https://www.linkedin.com/in/nebeyou-musie)
 - Gmail: nebeyoumusie@gmail.com
 - Telegram: [Nebeyou Musie](https://t.me/NebeyouMusie)
    
