# Liver Disease Prediction

**Project Description**
This project is on disease prediction using medical data, focusing on liver disease prediction. It aimed at developing predictive models to facilitate early detection and intervention for liver-related issues.

**Methodology Highlights: Data Collection -> Preprocessing -> Feature Engineering -> Model Development -> Model Evaluation**

**1. Data Collection:** 
      - Data source: https://www.kaggle.com/datasets/abhi8923shriv/liver-disease-patient-dataset/data

      - Feature number: 10

      - Dataset rows: 30691

   **Features description:**

      - Age: Age of the patient
      - Gender: Gender of the patient
      - Total Bilirubin (TB): Total bilirubin level in the blood
      - Direct Bilirubin (DB): Direct bilirubin level in the blood
      - Alkaline Phosphotase (Alkphos): Alkaline phosphatase enzyme level in the blood
      - Alamine Aminotransferase (SGPT): Alamine aminotransferase (also known as serum glutamate-pyruvate transaminase) level in the blood
      - Aspartate Aminotransferase (SGOT): Aspartate aminotransferase (also known as serum glutamic-oxaloacetic transaminase) level in the blood
      - Total Proteins (TP): Total protein level in the blood
      - Albumin (ALB): Albumin level in the blood
      - Albumin and Globulin Ratio (A/G Ratio): Ratio of albumin to globulin in the blood

  **Target:**
      - Result: 1 --> for liver patients and 2 --> for non-liver patients
      
**2. Preprocessing: including KNNImputer to fill missing data, encoding features and target** 

**3. Feature Engineering:** selecting the most relevant features to enhance model performance.

**4. Model Development:** Utilizing advanced machine learning techniques, including RandomForest and XGBoost algorithms.

**5. Model Evaluation:** used performance metrics such as accuracy, precision, recall, and F1-score.

