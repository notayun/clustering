# Sampling_Ayun_102167007



## Overview

Sampling is a crucial method employed in data analysis to extract insights about a population without the need to analyze every individual. In the context of fraud detection, an initial dataset imbalance of 763 non-fraudulent cases and only 9 fraudulent cases prompted the implementation of an oversampling approach. This involved generating additional instances of the minority class (fraudulent cases) to achieve a balanced dataset, consolidated into a single data frame.

## Sampling Techniques Utilized

1. **Simple Random Sampling:**
   - Random selection of samples from the population.

2. **Systematic Sampling:**
   - Regular interval selection after a random start.

3. **Cluster Sampling:**
   - Randomly selecting clusters from the population.

4. **Stratified Sampling:**
   - Division of the population into subgroups based on certain criteria.

5. **Bootstrap Sampling:**
   - Resampling with replacement to create multiple samples from the original dataset.

## Model Evaluation

Following the generation of five distinct samples using the mentioned sampling techniques, five models were applied to each sample.
<img src="img.png"></img>


## Conclusion

This comprehensive approach to model evaluation, utilizing diverse sampling techniques, provides a robust understanding of the fraud detection models' performance across different subsets of the data. The balanced dataset, coupled with the varied samples, ensures a more reliable assessment of model accuracy and effectiveness in detecting fraudulent cases.


