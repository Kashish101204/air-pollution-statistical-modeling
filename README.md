# Air-pollution-statistical-modeling
1. Methodology
This project uses Maximum Likelihood Estimation (MLE) to learn the probability density function (PDF) of NO₂ air pollution data collected from various locations in India.
<img width="1024" height="448" alt="image" src="https://github.com/user-attachments/assets/09e91f61-71f1-4d46-a49a-5b6bdac8fb4c" />
2. Description

Air pollution analysis is crucial for understanding environmental and public health risks.
In this project, NO₂ concentration data is statistically modeled using a Gaussian distribution.

Instead of relying on simple mean–variance estimation, Maximum Likelihood Estimation is used to obtain more accurate and reliable parameters. The learned probability density function helps understand the underlying distribution of NO₂ levels across India.

This notebook demonstrates the complete pipeline—from raw data to learned probabilistic model—using Python and scientific computing libraries.
3. Input / Output
Input

NO₂ air quality data (CSV format)

Dataset source: India Air Quality Dataset (Kaggle)

Output

Estimated parameters:

μ (mean)

λ (lambda)

c (normalization constant)

Histogram of transformed data

Learned Gaussian PDF plotted over the data
5. Screenshot of the Interface
