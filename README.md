# Deep-Learning

## Analysis Overview
The purpose of this analysis is to create a tool that can help the nonprofit organization, Alphabet Soup, select the best applicants for funding; the best applicants are those who have a higher chance of success in their ventures. A binary classifier was created with the provided dataset and knowledge of machine learing and neural networks. The dataset contains more than 34,000 organizations who've received funding from Alphabet Soup over the years. 

## Results

### Data Preprocessing
  - Target variable for model: IS_SUCCESSFUL
  - Feature variables for model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
  - Removed variables for model: EIN and NAME

### Compiling, Training, and Evaluating the Model
There are a total of four neural network models.  My first attempt is titled AlphabetSoupCharity, and the three after are titled AlphabetSoupCharity_Optimation (1, 2, and 3). I selected the following for the neural network models:
  - Number of neurons: [8, 8], [16, 16, 16, 16], [5, 5], [16, 16, 8]
  - Number of layers: 2, 4, 2, 3
  - Activation function: sigmoid, sigmoid, sigmoid, relu

Steps to increase model performance
  - Change bin limits for appapplication and classifation bins
  - Change number of layers
  - Change activation function types
  - Change number of epochs

## Summary
Overall, I was only able to achieve a 73.3% accuracy rate, while the goal was 75% or above. I'd recommend constructing more hidden layers and utilizing the .Choice function. I tried this method, but was unsuccessful. 
