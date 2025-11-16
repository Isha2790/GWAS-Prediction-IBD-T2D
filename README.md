# GWAS-Prediction-IBD-T2D: Genomic Risk Prediction Model

## Project Summary
This project develops a **Machine Learning (ML) model** to predict genetic risk for **Inflammatory Bowel Disease (IBD)** and **Type-II Diabetes (T2D)**. We focused on building a reliable pipeline and validating model performance on specialized genomic data.

## Timeline & Status
* **Developed:** Jan – May 2024 (B.Tech Academic Project).
* **Current Status:** Code uploaded to GitHub (Nov 2025) for professional portfolio review.

## Technical Focus
This project demonstrates expertise in Data Science and ML Engineering principles through:

1.  **Data Handling:** Processing and feature engineering of large-scale **GWAS Summary Statistics**.
2.  **Model Validation:** Used cross-validation to measure model strength using **Accuracy, F1-Score, and Recall**.
3.  **Algorithm:** Implemented the **[FILL IN YOUR SPECIFIC ML MODEL HERE]** algorithm for Polygenic Risk Scoring (PRS).

### My Contribution (In Group Project)
**I worked on the Random Forest Algorithm and calculated the performance metrics of the ML Model, including accuracy, precision, recall, and F1-score. I have also made the ROC and AUC curve graph based on the results of the ML model, and also made heat maps based on the results**


## Setup and Execution

### Prerequisites
* Python 3.x
* Virtual Environment recommended.

### Installation
1.  Clone the repository:
    ```bash
    git clone [https://github.com/Isha2790/GWAS-Prediction-IBD-T2D.git](https://github.com/Isha2790/GWAS-Prediction-IBD-T2D.git)
    cd GWAS-Prediction-IBD-T2D
    ```
2.  Install required libraries:
    ```bash
    pip install -r requirements.txt 
    ```
### ⚠️ Data Note
The full genomic data is **not included** due to file size limitations. The **GWAS Summary Statistics** were sourced from a publicly available consortium (e.g., **UK Biobank** or **NHGRI-EBI GWAS Catalog**). The required files must be downloaded separately for full execution.

### Run Prediction
* Execute the main script:
  ```bash
  python run_prediction.py
