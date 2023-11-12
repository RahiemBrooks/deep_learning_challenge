# Deep Learning Model Performance Report for Alphabet Soup

## Analysis Overview

In this section, we present a detailed report on the performance of the deep learning model developed for Alphabet Soup.

## Analysis Components

### Data Preprocessing

#### Target and Feature Variables

- **Target Variable(s):** The 'IS_SUCCESSFUL' column from `application_df`.
- **Feature Variable(s):** All columns from `application_df` except 'IS_SUCCESSFUL'.
- **Excluded Variables:** 'EIN' and 'NAME' columns were removed as they are neither targets nor features in the dataset.

### Model Compilation, Training, and Evaluation

#### Neural Network Configuration

1. **Neurons, Layers, and Activation Functions:**
   - Initial attempt: 8 hidden nodes for layer 1 and 5 hidden nodes for layer 2, chosen iteratively in subsequent attempts.
  
2. **Target Model Performance:**
   - The model fell short of the 75% accuracy target.

3. **Performance Enhancement Attempts:**
   - Strategies included adding layers, removing columns, adjusting hidden nodes, and changing activation functions in pursuit of improved accuracy.

## Summary

The deep learning model achieved an overall accuracy of approximately 73% in predicting the classification problem. To enhance accuracy, it is recommended to improve the correlation between input and output. This can be accomplished through thorough data cleanup upfront and experimenting with different activation functions in model layers. Iterative refinement is advised to achieve higher accuracy.