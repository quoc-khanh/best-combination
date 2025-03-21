# Best Combination

This project explores various credit scoring datasets, balancing techniques, and classification models to determine the optimal combination of balancing technique and model.

## Overview

A key challenge in credit scoring datasets is the high class imbalance, typically addressed using techniques like SMOTE (Synthetic Minority Over-sampling Technique). However, is SMOTE truly the most effective method? This repository conducts extensive testing across a wide range of data balancing techniques to evaluate their effectiveness and identify the best approach.

To represent Neural Network-based techniques, we used the cWGAN model. Full credit is given to the original author, referenced in *S0957417421000233.txt*.

Experiments were conducted on [Kaggle](https://www.kaggle.com/code/trnmqkhnh/best-combination), leveraging its free resources and ability to run up to five kernels simultaneously.

## Repository Structure

```
/best-combination │-- First step │-- Second step │-- Second step with cWGAN
```

## Methodology

1. **Model Selection**: Initial tests were conducted to choose suitable classification models. (See *First step*).
2. **Balancing Techniques**: Various data balancing techniques were applied and evaluated to determine the most effective approach. (See *Second step* and *Second step with cWGAN*).
3. **Results & Analysis**: Experimental results are documented in *result_csv.xlsx* and *Result.pdf*.

## Results

The findings provide insights into the effectiveness of different balancing techniques in credit scoring datasets, helping identify the best-performing combination of model and balancing method.

For detailed analysis and results, refer to the Kaggle notebook: [Best Combination](https://www.kaggle.com/code/trnmqkhnh/best-combination).
