# 📚 Student Lifestyle and Academic Performance Prediction 📈

## 🌟 Project Overview

This project dives into the fascinating relationship between a student's lifestyle and their academic performance, including stress levels. By analyzing a dataset of student lifestyle factors, such as study hours, extracurricular activities, sleep, physical activity, and social engagement, we aim to predict their GPA and stress level.

## 📊 Dataset

Our analysis leverages the `student_lifestyle_dataset.csv` file, containing valuable information on 2,000 students. The dataset includes the following key features:

- **StudentID:** Unique identifier for each student 🧑‍🎓
- **Study_Hours_Per_Day:** Number of hours dedicated to studying daily 📖
- **Extracurricular_Hours_Per_Day:** Number of hours spent on extracurricular activities daily ⚽
- **Sleep_Hours_Per_Day:** Number of hours of sleep daily 😴
- **Physical_Activity_Hours_Per_Day:** Number of hours engaged in physical activity daily 🏃‍♀️
- **Social_Hours_Per_Day:** Number of hours spent socializing daily 💬
- **Stress_Level:** Categorized as Low, Moderate, or High 😥
- **GPA:** Student's Grade Point Average (GPA)  💯

## 🚀 Methodology

Our project follows a structured approach to analyze the data and build predictive models:

1. **Data Loading and Exploration:**
   - We load the dataset using Pandas, a powerful data analysis library in Python. 🐼
   - We explore the data's distribution and relationships between variables using descriptive statistics and visualizations. 📊
   - Visualizations provide valuable insights into the data's patterns and trends. 📉
2. **Data Preparation:**
   - A pipeline is created for data preprocessing to ensure data quality and consistency. ⚙️
   - Numerical features are imputed with the median to handle missing values. 🧮
   - Categorical features are encoded using Ordinal Encoding to convert them into numerical representations. 🔢
3. **Model Selection and Training:**
   - We train and evaluate various regression models for GPA prediction, including Linear Regression, Decision Tree Regression, Random Forest Regression, and Support Vector Regression. 🧪
   - Cross-validation is employed for model evaluation, ensuring robust and reliable performance estimates. 🔄
   - A classification model would be necessary for stress level prediction. 🎯
4. **Model Evaluation and Selection:**
   - The model demonstrating the best performance on the test set is selected as our final model.🏆
   - Linear Regression emerged as a strong performer for GPA prediction in our analysis.🥇
5. **Prediction:**
   - The final model is used to predict GPA and stress levels for new, unseen data, providing valuable insights into student performance.🔮

## 💻 Usage

Ready to explore the project? Follow these simple steps:

1. Clone the repository to your local machine. 📥
2. Install the necessary libraries using pip:
```bash pip install pandas scikit-learn matplotlib seaborn```
3. Upload the `student_lifestyle_dataset.csv` file to the project directory. 📁
4. Run the Jupyter Notebook `Student_Lifestyle_Prediction.ipynb` to execute the analysis. 🚀

## 🎯 Results

- Our project sheds light on the intricate relationship between student lifestyle factors, academic performance, and stress levels. 💡
- The selected models provide reasonable predictions for GPA and stress levels, offering valuable insights for students and educators. ✨

## 🙌 Contributing

We encourage contributions from the community to further enhance this project! Feel free to open issues or pull requests to share your ideas and improvements.🤝
