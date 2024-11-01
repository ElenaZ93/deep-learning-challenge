# Deep Learning Challenge: Predicting Success for Alphabet Soup Funded Organizations

## Background

Alphabet Soup, a nonprofit foundation, wants a tool to help it select applicants for funding who are most likely to succeed in their ventures. Using machine learning and neural networks, this project aims to create a binary classifier to predict whether an applicant will be successful if funded by Alphabet Soup.

The provided dataset contains information on over 34,000 organizations that have received funding. Key features of this dataset include:

- `EIN` and `NAME`: Identification columns
- `APPLICATION_TYPE`: Type of application submitted to Alphabet Soup
- `AFFILIATION`: Industry affiliation
- `CLASSIFICATION`: Government organization classification
- `USE_CASE`: Purpose of requested funding
- `ORGANIZATION`: Type of organization
- `STATUS`: Active status of the organization
- `INCOME_AMT`: Income classification
- `SPECIAL_CONSIDERATIONS`: Special application considerations
- `ASK_AMT`: Amount of funding requested
- `IS_SUCCESSFUL`: Outcome indicator of the funding’s success

## Instructions

### Before You Begin
1. **Create a new repository** named `deep-learning-challenge`.
2. Clone the new repository to your local machine.
3. Create a directory within your repository for the Deep Learning Challenge and push these changes to GitHub.

### Files
The necessary files for this project can be downloaded from the [Resources folder](https://github.com/ElenaZ93/deep-learning-challenge/blob/f35e5f05e01079f49f2692c143f7af38488ec9e0/Resources/Starter_Code-checkpoint.ipynb).

---

## Project Steps

### Step 1: Preprocess the Data
Using **Pandas** and **scikit-learn’s StandardScaler()**, preprocess the dataset to prepare for model compilation, training, and evaluation in Step 2.

1. Upload `charity_data.csv` to Google Colab and load it into a Pandas DataFrame.
2. Identify target variables for your model.
3. Select feature variables.
4. Drop irrelevant columns (such as `EIN` and `NAME`).
5. For columns with more than 10 unique values, set a cutoff to combine rare categorical values.
6. Encode categorical variables using `pd.get_dummies()`.
7. Split the data into training and testing sets.
8. Scale the feature data using `StandardScaler`.

### Step 2: Compile, Train, and Evaluate the Model
Using **TensorFlow** and **Keras**, design and build a neural network for binary classification to predict the success of funded organizations.

1. Define input features and nodes.
2. Create hidden layers with appropriate activation functions.
3. Add an output layer.
4. Compile and train the model, setting up a callback to save model weights every five epochs.
5. Evaluate model performance using test data.
6. Save the model results in `AlphabetSoupCharity.h5`.

### Step 3: Optimize the Model
Adjust model parameters to achieve a target accuracy greater than 75%.

1. **Data Adjustments**: Remove or bin columns, adjust cutoff points, and combine rare occurrences.
2. **Network Adjustments**: Add neurons or layers, adjust activation functions, and tune epoch counts.
3. Save optimized results to `AlphabetSoupCharity_Optimization.h5`.

### Step 4: Report on the Model
Write a report detailing the performance of your deep learning model.

- **Overview**: Explain the purpose of the analysis.
- **Results**:
  - **Data Preprocessing**: Identify target, feature, and irrelevant variables.
  - **Model Training**: Describe chosen neurons, layers, and activation functions.
  - **Model Performance**: Report accuracy and any optimization efforts.
- **Summary**: Summarize results and recommend alternative models.
- The questions are:
  The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

- Data Preprocessing

1. What variable(s) are the target(s) for your model?
2. What variable(s) are the features for your model?
3. What variable(s) should be removed from the input data because they are neither targets nor features?

- Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
2. Were you able to achieve the target model performance?
3. What steps did you take in your attempts to increase model performance?
   
-  Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

### Step 5: Finalize Submission
1. Download Colab notebooks to your computer.
2. Add them to the `deep-learning-challenge` directory in your local repository.
3. Push changes to GitHub.

---

## Resources
- Download the necessary files from the [Resources folder](https://github.com/ElenaZ93/deep-learning-challenge/blob/f35e5f05e01079f49f2692c143f7af38488ec9e0/Resources/Starter_Code-checkpoint.ipynb).

---

## Technologies Used
- **Pandas** for data manipulation
- **scikit-learn** for preprocessing
- **TensorFlow** and **Keras** for neural network development

## License
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/
