# 📘 Learning Probability Density Functions using Roll-Number-Parameterized Non-Linear Model

## 📌 Overview

This project demonstrates how a non-linear, roll-number-dependent transformation can be applied to real-world environmental data and how the probability density function (PDF) of the transformed data can be learned using statistical estimation techniques.

The experiment uses NO₂ concentration data from the India Air Quality dataset and models the transformed feature using a Gaussian probability density function.

## 📂 Dataset Description

Dataset: India Air Quality Data

Source: Kaggle
https://www.kaggle.com/datasets/shrutibhargava94/india-air-quality-data

Feature Used: NO2 (Nitrogen Dioxide concentration)

Missing values in the feature were removed before processing.

## Parameter Estimation

The parameters are estimated using Maximum Likelihood Estimation (MLE), which is the standard method for fitting Gaussian distributions.

## 📊 Results
Estimated Parameters

The learned parameters of the probability density function are summarized below:

Parameter	Value
μ (Mean) = 25.8130
λ (Lambda) = 0.001461
c (Normalization Constant) = 0.021565

These values define the final learned probability density function for the transformed NO₂ feature.

## 📈 Result Graph

<img width="708" height="470" alt="image" src="https://github.com/user-attachments/assets/e13e03e5-9c11-46d9-8baf-151f1f603158" />

Description of the Graph:

The histogram represents the empirical distribution of the transformed variable z.

The red curve represents the learned Gaussian probability density function using the estimated parameters.

The close alignment between the histogram and the PDF curve indicates a good statistical fit.

Interpretation:

The transformation preserves the overall structure of the data while adding non-linearity.

The Gaussian model captures the central tendency and dispersion of the transformed variable effectively.

This confirms that the chosen PDF and estimation method are appropriate for the transformed data.

## ✅ Key Observations

Roll-number-based parameterization ensures uniqueness across students.

The transformed feature follows an approximately normal distribution.

Maximum Likelihood Estimation provides stable and interpretable parameter values.

Visualization confirms the validity of the learned PDF.

## 🧠 Conclusion

This project successfully demonstrates how a roll-number-dependent non-linear transformation can be applied to real-world data and how the probability density function of the transformed variable can be learned using statistical estimation techniques. The learned Gaussian PDF provides a reliable approximation of the underlying distribution of the transformed NO₂ values.

## 🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib
