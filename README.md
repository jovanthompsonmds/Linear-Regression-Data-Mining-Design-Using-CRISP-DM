# Linear Regression Data Mining Design Using CRISP-DM

## Overview
This project uses the CRISP-DM methodology to explore the relationship between midterm and final exam grades through a predictive linear regression model. The goal is to predict final exam grades based on midterm performance, offering educators actionable insights for improving student outcomes.

## Features
- **CRISP-DM Phases**: The project follows all six phases of CRISP-DM: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment.
- **Linear Regression Modeling**: The model predicts final grades from midterm scores, quantifying their relationship with key metrics like R-squared and p-values.
- **Data Visualization**: Scatterplots and regression lines visualize grade relationships, aiding in understanding trends and predictions.

## Files
1. **Data Mining Design Using CRISP-DM.pdf**  
   The full project report, detailing the CRISP-DM phases, analysis, and results.
2. **Jupyter Notebook**  
   Code implementing linear regression, generating visualizations, and calculating key metrics.

## Requirements
- Python 3.8 or higher
- Required Python libraries:
  - `matplotlib`
  - `numpy`
  - `statsmodels`
  - `scipy`

Install the dependencies using:
pip install matplotlib numpy statsmodels scipy

## Usage
1. Clone the repository:
git clone https://github.com/jovanthompsonmds/Linear-Regression-Data-Mining-Design-Using-CRISP-DM.git

2. Open the Jupyter Notebook and run the code to:
- Load the data
- Perform linear regression
- Visualize the results
- Analyze the relationship between midterm and final exam grades

## Insights & Conclusions
The analysis shows a moderately strong positive linear relationship between midterm and final grades, with an R-squared value of 0.613. The predictive model can help educators identify students who may need extra support and provide data-driven insights for improving academic strategies.

### **1. Objective & Business Understanding**
- The project applies **CRISP-DM methodology** to predict a **student's final exam grade** based on their **midterm exam score**.
- This predictive model can **assist educators** in identifying students who may need additional support to improve their final performance.
- The study also helps gauge **overall course performance** based on early assessments.

### **2. Data Understanding & Preparation**
- The dataset consists of **midterm and final exam scores** for **12 students**.
- **Midterm scores (X):** Ranged from **33% to 94%**.
- **Final scores (Y):** Ranged from **49% to 90%**.
- **No missing values, outliers, or data transformations** were necessary.

### **3. Model Selection & Justification**
- **Simple Linear Regression** was chosen as the most suitable model to predict final grades based on midterm grades.
- The model quantifies the **linear relationship** between midterm and final scores.

## **4. Results & Evaluation**

### Regression Equation:
\[
y = 0.5816x + 32.0279
\]
where:
- **x** = Midterm Grade
- **y** = Predicted Final Grade

### Performance Metrics:
- **R² = 0.613** (61.3% of the variance in final grades is explained by midterm scores).
- **p-value = 0.00261** (statistically significant).
- **Slope (0.582):** A **1-point increase** in the midterm score increases the predicted final exam grade by **0.58 points**.

### Example Prediction:
- For a **midterm score of 86%**, the model predicts a **final grade of 82.05%**.

## **5. Visualizations & Interpretation**
- **Scatter plot** of midterm vs. final grades **shows a positive correlation**.
- **Red regression line** illustrates the model’s prediction trend.

## **6. Deployment & Real-World Applications**
The model was **implemented in Jupyter Notebook**, allowing **real-time predictions**.

### Potential Use Cases:
- **Educational interventions:** Identify students at risk of failing.
- **Performance tracking:** Estimate course outcomes based on midterm performance.
- **Adaptive learning strategies:** Adjust teaching methods based on predicted student performance.

## **7. Conclusion**
- The model successfully demonstrates a **moderately strong** linear relationship between **midterm and final exam scores**.
- The **CRISP-DM methodology** ensures a **structured and systematic** approach to data mining.
- This model can serve as a **useful decision-support tool** for educators and academic institutions.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to improve the project.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

Developed by Jovan Thompson as part of a data science portfolio project.
