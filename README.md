**This is a Playlist Generator Project that utilizes a machine learning linear regression model to predict target variables based on selected features.** 
## Steps

### 1. Data Acquisition:

- Found a suitable dataset containing information about songs features like tempo, danceability, energy, etc. and their popularity based on Spoitfy through Kaggle. 

### 2. Data Preprocessing:

- Loaded the dataset into a Pandas DataFrame.
- Handled missing values and cleaned the data.
- Explored the dataset to understand the features and target variable.
  
### 3. Feature Selection:

- Identifed the features that are relevant for predicting the target variable and determined correlations.
  
### 4. Train-Test Split:

- Split the dataset into training and testing sets to evaluate the model's performance.

### 5. Model Training:

- Used Scikit-learn to train a linear regression model.
- Defined features (X) and the target variable (y).
- Fit the model on the training data.

### 6. Model Evaluation:

- Evaluated the model on the test set using metrics like Mean Squared Error (MSE) and R-squared.

### 7. Playlist Generation:

- Used the trained model to predict the target variable for new songs.
- Ranked the songs based on the predicted values.
- Generated playlists by selecting the top-ranked songs.

### 8. Data Visualization:

- Used Matplotlib and Seaborn to visualize the relationships between features and the target variable.
- Plot predicted values against true values to visualize the model's performance.

### 9. Web Application:

- Created web application to interact with the playlist generator.
- Implemented routes for user input and playlist display.
