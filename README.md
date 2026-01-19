# 🌫️ Air Pollution Statistical Modeling

---

## 1. Methodology

This project uses **Maximum Likelihood Estimation (MLE)** to learn the **probability density function (PDF)** of **NO₂ air pollution data** collected from various locations across India.

The workflow includes:
- Loading and preprocessing NO₂ air quality data
- Applying a nonlinear transformation to the data
- Defining a Gaussian probability density function
- Estimating parameters using numerical MLE optimization
- Visualizing the learned distribution against the data

<p align="center">
  <img width="1024" height="448" alt="Methodology Workflow" src="https://github.com/user-attachments/assets/09e91f61-71f1-4d46-a49a-5b6bdac8fb4c" />
</p>

---

## 2. Description

Air pollution analysis plays a critical role in understanding **environmental and public health risks**.  
In this project, **NO₂ concentration data** is statistically modeled using a **Gaussian distribution**.

Instead of relying on simple mean–variance estimation, **Maximum Likelihood Estimation (MLE)** is employed to obtain **more accurate and reliable parameters**.  
The learned probability density function provides insights into the underlying distribution of NO₂ levels across India.

This notebook demonstrates the **complete pipeline**—from raw data ingestion to probabilistic modeling—using **Python and scientific computing libraries**.

---

## 3. Input / Output

### 📥 Input
- NO₂ air quality data (CSV format)
- Dataset source: **India Air Quality Dataset (Kaggle)**

### 📤 Output
- Estimated statistical parameters:
  - **μ (mean)**
  - **λ (lambda)**
  - **c (normalization constant)**
- Histogram of transformed NO₂ data
- Learned Gaussian PDF plotted over the data distribution

---

## 4. Screenshot of Probability Graph

<p align="center">
  <img width="886" height="590" alt="Probability Distribution Graph" src="https://github.com/user-attachments/assets/515b2080-61ce-44ba-b9f2-330dda63b487" />
</p>

---

## 🛠️ Tech Stack
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- SciPy  
- KaggleHub  

---

## 👩‍💻 Author
**Kashish Gupta**
