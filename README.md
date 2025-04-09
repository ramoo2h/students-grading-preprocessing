# Students Grading Dataset - Data Preprocessing

This project implements full data preprocessing on the [Students Grading Dataset](https://www.kaggle.com/datasets/mahmoudelhemaly/students-grading-dataset).

## 📌 Preprocessing Steps

1. **Data Cleaning**
   - Handled missing values
   - Removed duplicates
   - Removed outliers using IQR

2. **Data Integration**
   - Added synthetic student records

3. **Data Reduction**
   - PCA
   - Feature selection based on correlation

4. **Data Transformation**
   - Normalization (MinMaxScaler)
   - Discretization of scores into grade bins (A-F)

5. **Other Techniques**
   - Linear Regression to predict scores
   - KMeans clustering of students
   - Random sampling (20%)

## 📁 Files Included
- `students_preprocessing.py` – Full preprocessing code
- `processed_students_data.csv` – Final cleaned dataset

---

✅ Created for assignment purposes.
