# 🎵 Music Trend Analysis

## 📌 Project Overview  
This project explores the key factors influencing **song popularity**, focusing on **audio features, song characteristics, and streaming trends**. Using **regression models and statistical analysis**, we examine how various musical attributes contribute to a song’s success and provide **data-driven insights for artists, producers, and marketers**.

---

## 🎯 Key Objectives
- Assess the relationship between **song popularity** and **audio features** like **danceability, energy, valence, and instrumentalness**.
- Identify **key factors that contribute to viral songs** using **exploratory data analysis**.
- Develop **predictive models** to forecast **song success based on audio characteristics**.
- Provide insights to **help musicians optimize song composition and production**.

---

## 📂 Dataset
- **Source**: [Kaggle - Song Popularity Dataset](https://www.kaggle.com/datasets/yasserh/song-popularity-dataset)
- **Contains**: 12,000+ songs
- **Features Include**:
  - 🎼 **Audio Features**: Danceability, Energy, Loudness, Speechiness, Valence, Tempo
  - 🎵 **Metadata**: Key, Mode, Duration, Release Year
  - 📊 **Popularity Score** (0-100)

---

## 🛠 Technologies Used
- **Programming**: Python (Pandas, NumPy, Scikit-learn)
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Multilinear Regression, Polynomial Regression
- **Statistical Techniques**: Correlation Analysis, Feature Engineering, Scaling

---

## 📊 Key Insights From Exploratory Data Analysis
- **Energy and Loudness** show a **strong positive correlation (+0.77)**, indicating that **louder songs tend to have higher energy**.
- **Danceability and Valence** (happiness) **positively correlate** with **higher song popularity**.
- **Speechiness has a nonlinear effect**: Too much spoken content reduces popularity unless in the **rap genre**.
- **Hit songs tend to have higher Danceability, Energy, and Loudness**, while **non-hit songs are more acoustic**.

---

## 📈 Machine Learning Models and Performance
| **Model**                     | **R² Score (Training)** | **R² Score (Testing)** | **Key Observations** |
|-------------------------------|-------------------------|-------------------------|-----------------------|
| **Multilinear Regression**     | 62.39%                  | 62.22%                  | Speechiness, Valence, and Instrumentalness were key predictors |
| **Polynomial Regression (Degree 2)** | 66.43%                  | 65.57%                  | Captured nonlinear relationships, improving prediction accuracy |

---

## 🔍 Key Findings
✔️ **Hit songs tend to have higher danceability, energy, and loudness**.  
✔️ **Non-hit songs are often more acoustic and have lower speechiness**.  
✔️ **Polynomial Regression improved prediction accuracy by 4%** over linear models.  
✔️ **Speechiness, valence, and instrumentalness were the most influential features** in predicting song popularity.  

---

## 🎶 Recommendations for Musicians & Producers
🎵 **Optimize Danceability & Energy** – Upbeat and engaging tracks **resonate more** with listeners.  
🎧 **Balance Speechiness** – Too much spoken content reduces popularity **unless targeting rap listeners**.  
📊 **Leverage Data Insights** – Use **feature analysis** to guide **music production & marketing strategies**.  
🚀 **Explore Nonlinear Trends** – Consider **interaction effects** between tempo, loudness, and valence when composing songs.  

---
📄 **[Code for Exploratory Data Analysis](https://github.com/adyareddy15/Data-and-Programming-Project/blob/main/Code%20for%20Exploratory%20Data%20Analysis.pdf)**

📄 **[Data Description & Visualization](https://github.com/adyareddy15/Data-and-Programming-Project/blob/main/Data%20Description%20and%20Visualization.pdf)**
