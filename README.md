# Student Sleep Patterns Analysis and Study Recommendations

This project focuses on analyzing and understanding student sleep patterns using data from Kaggle. It leverages data preprocessing, exploratory data analysis (EDA), data visualization, and deep learning techniques to derive actionable insights and personalized study recommendations based on circadian rhythms.

---

## Dataset

The dataset used in this project is sourced from Kaggle:
[Student Sleep Patterns](https://www.kaggle.com/datasets/arsalanjamal002/student-sleep-patterns?select=student_sleep_patterns.csv)

The dataset includes information about:
- Sleep duration
- Study hours
- Sleep quality
- Circadian preferences (morning larks vs. night owls)
- University year and other relevant attributes

---

## Project Objectives

1. **Understand Sleep Patterns:**
   - Analyze sleep duration, quality, and study habits of students.
2. **Visualize Key Trends:**
   - Use visualizations to identify correlations between academic performance, sleep quality, and study hours.
3. **Optimize Study Recommendations:**
   - Provide tailored study schedules based on students' circadian preferences using deep learning models.
4. **Predict Sleep Quality:**
   - Employ deep learning techniques to predict sleep quality from various factors.

---

## Steps and Workflow

### 1. **Data Loading and Preprocessing**
- Convert time values to a standard format (`HH:MM:SS`) for analysis.
- Handle missing values and normalize data for model compatibility.
- Feature engineering to extract circadian preferences and optimal study windows.

### 2. **Exploratory Data Analysis (EDA)**
- Analyzed sleep duration, study hours, and academic year impacts.
- Explored correlations between sleep quality and study performance.

### 3. **Data Visualization**
- **Histogram for Sleep Duration and Study Hours:** Showcased typical sleep and study patterns.
- **Box Plot of Sleep Quality by University Year:** Visualized variation in sleep quality across academic years.
- **Pairplot for Correlation Analysis:** Revealed relationships between numerical variables.

### 4. **Deep Learning Model**
- Built and trained a deep learning model to predict sleep quality based on study hours, sleep duration, and other features.
- Fine-tuned the model to improve accuracy and reduce overfitting.

### 5. **Study Recommendations**
- Generated personalized study schedules by aligning study hours with students' circadian rhythms (morning larks vs. night owls).

---

## Key Results and Insights

- **Circadian Preferences:** Identified distinct differences in sleep quality and study performance based on circadian rhythms.
- **Visual Trends:** Demonstrated how academic year impacts sleep quality and study habits.
- **Prediction Model:** Achieved reliable predictions for sleep quality using a deep learning approach.
- **Actionable Insights:** Recommended study windows tailored to individual sleep patterns, enhancing productivity and well-being.

---

## Tools and Technologies

- **Programming Language:** Python
- **Libraries and Frameworks:**
  - `pandas`, `numpy` for data preprocessing
  - `matplotlib`, `seaborn` for data visualization
  - `scikit-learn` for initial machine learning experiments
  - `TensorFlow`/`Keras` for deep learning
- **Jupyter Notebook:** Used for development and documentation

---
