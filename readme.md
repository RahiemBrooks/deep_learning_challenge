# Deep Learning Challenge: Alphabet Soup Charity

## Background

Alphabet Soup, a nonprofit foundation, aims to select funding applicants with the highest chance of success using a binary classifier based on provided data. This dataset includes information on over 34,000 organizations that have received Alphabet Soup funding. Key columns include EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, and IS_SUCCESSFUL.

## Step 1: Preprocess the Data

### Tasks:

1. **Read and Identify:**
   - Read charity_data.csv into a Pandas DataFrame.
   - Identify the target variable(s) and feature variable(s).
   - Drop EIN and NAME columns.

2. **Unique Values and Binning:**
   - Determine the number of unique values for each column.
   - For columns with over 10 unique values, analyze data points for each unique value.
   - Bin rare categorical variables together as "Other."

3. **Encode Categorical Variables:**
   - Use pd.get_dummies() to encode categorical variables.

4. **Split and Scale:**
   - Split data into features array (X) and target array (y).
   - Use train_test_split to create training and testing datasets.
   - Scale training and testing features using StandardScaler.

## Step 2: Compile, Train, and Evaluate the Model

### Tasks:

1. **Neural Network Design:**
   - Create a neural network model using TensorFlow and Keras.
   - Determine input features and nodes for each layer.

2. **Hidden Layers and Activation:**
   - Create the first hidden layer with an appropriate activation function.
   - Add a second hidden layer if necessary, with an appropriate activation function.
   - Design the output layer with an appropriate activation function.

3. **Compile and Train:**
   - Check the model's structure.
   - Compile and train the model.
   - Implement a callback to save model weights every five epochs.

4. **Evaluation:**
   - Evaluate the model using test data to calculate loss and accuracy.

5. **Save Results:**
   - Save and export results to AlphabetSoupCharity.h5.

## Step 3: Optimize the Model

### Tasks:

1. **Optimization Attempts:**
   - Adjust input data to address model confusion (e.g., drop columns, create more bins).
   - Modify hidden layers and neurons.
   - Use different activation functions.
   - Adjust epochs in the training regimen.

2. **Create Optimization Notebook:**
   - Create AlphabetSoupCharity_Optimization.ipynb.
   - Import dependencies and read charity_data.csv.
   - Preprocess the dataset with adjustments from optimization attempts.

3. **Optimized Model Design:**
   - Design a neural network model with modifications for higher than 75% accuracy.

4. **Save Optimized Results:**
   - Save and export optimized results to AlphabetSoupCharity_Optimization.h5.