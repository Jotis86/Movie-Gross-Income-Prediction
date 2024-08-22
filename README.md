# 🎬✨ Movie Gross Income Prediction Project 🎥💰

## 🎯 Objective
- The objective of this project is to predict the gross income of a movie using a machine learning model. Various features of the movies, such as budget, genre, director, IMDB and MovieLens ratings, and duration, have been used for this purpose. This project aims to provide a useful tool for film studios and producers, helping them estimate the potential financial success of their movies before release. 🎯🎬💡

## ⚙️ Functionality
- 📥 Load and clean the dataset.
- 📊 Visualize the data to understand relationships between features.
- 🧠 Training a machine learning model to predict the gross income of a movie.
- 📊 Evaluating the model’s performance using metrics such as MSE, RMSE, MAE, MAPE, and R².
- 🤖 Comparing different machine learning models to determine which one offers the best performance.
- 📈 Visualizing the results and relationships between variables to gain a deeper understanding of the data.

## 🛠️ Tools Used
- Python 🐍: Main programming language used for the project development.
- Pandas 🐼: Library used for data manipulation and analysis, allowing easy data loading and transformation.
- Scikit-learn 🔍: Machine learning library used for building, training, and evaluating models.
- Jupyter Notebook 📓: Interactive environment used for development and visualization of results, facilitating experimentation and analysis.

## 🛠️ Development Process
- Data Loading and Preprocessing 📥🔄:
   - Data Loading: Movie data is loaded from a CSV file using Pandas.
   - Preprocessing: Data is preprocessed using ColumnTransformer and OneHotEncoder for handling categorical variables and StandardScaler for standardizing numerical variables.
- Pipeline Definition 🛤️:
   - Pipeline: A pipeline is defined that includes the preprocessor and the regression model. This allows chaining multiple preprocessing and modeling steps into a single structure, facilitating workflow management and reproducibility.
- Training Multiple Models 🏋️‍♂️:
   - Models: Several machine learning models, including linear regression, Random Forest, and Gradient Boosting, are trained to determine which one offers the best performance. Each model is evaluated using a set of metrics to compare their performance.
- Hyperparameter Tuning 🔧:
   - GridSearchCV: GridSearchCV is used to perform an exhaustive search for the best combination of hyperparameters for the Random Forest model. This involves testing multiple parameter combinations and selecting the one that minimizes prediction error.
- Model Training 🏆:
   - Training: The model is trained using the training data and the best combination of hyperparameters found in the previous step. The model is adjusted to minimize prediction error and improve accuracy.
- Model Evaluation 🧪:
   - Evaluation: The model’s performance is evaluated using the test data and various metrics, including MSE, RMSE, MAE, MAPE, and R². These metrics provide a comprehensive view of the model’s performance and its ability to generalize to new data.

## 📊 Results
- These results indicate that the tuned Random Forest model provides good accuracy in predicting the gross income of movies, with an R² of 0.493, meaning the model explains approximately 49.3% of the variability in the gross income data. 📈🎉
   - MSE: 28221.46
   - RMSE: 167.99
   - MAE: 112.03
   - MAPE: 0.288
   - R²: 0.493

## 📈 Visualizations
- Distribution of Numerical Variables 📊: Shows the distribution of numerical variables such as budget, ratings, and movie duration. This helps understand the dispersion and central tendency of these variables.
- Distribution of Categorical Variables 📊: Shows the distribution of categorical variables such as genre and director of the movies. This allows identifying the most common categories and their frequency.
- Relationships between Variables 🔗: Visualizes the relationships between different variables to identify possible correlations. This is useful for understanding how variables interact with each other and affect gross income.
 - Outlier Identification 🚨: Identifies outliers in numerical variables using box plots. Outliers can significantly influence model performance and it is important to identify and handle them appropriately.
- Gross Income by Studio 🏢: Shows the total gross income by film studio. This allows identifying which studios have better financial performance.
- Gross Income by Day of the Week 📅: Shows the total gross income by day of the week. This can reveal patterns in income behavior based on the movie release day.
- Correlation Analysis 🔍: Shows a heatmap of correlations between variables. This helps identify strong relationships between variables that can be useful for modeling.
- Bar Chart for MSE, RMSE, MAE, and MAPE 📊: Compares error metrics for different models. This allows evaluating and comparing the performance of each model in terms of accuracy.
- Bar Chart for R² 📊: Compares the R² coefficient for different models. This shows which model best explains the variability in the data.
- Grouped Bar Chart for MSE, RMSE, MAE, and MAPE 📊: Compares grouped error metrics for different models. This provides a comparative view of error metrics in a single chart.
- Line Chart for R² 📈: Shows the evolution of the R² coefficient for different models. This allows visualizing how the model’s performance changes with different configurations.
- Predictions vs Actual Values Chart 🔍: Compares the model’s predictions with the actual values. This helps evaluate the model’s accuracy and identify possible deviations.
- Error Distribution Chart 📊: Shows the distribution of prediction errors. This is useful for understanding the magnitude and direction of the errors made by the model.
- Boxplot of Errors by Genre 🎥: Shows the distribution of prediction errors by movie genre. This allows identifying if the model has a bias towards certain genres.

## 📂 Project Structure
- The project is organized as follows:
  - Data
  - Notebook

## 📝 Conclusions
- The tuned Random Forest model showed the best performance with an R² of 0.493. 🏆
- Data preprocessing and hyperparameter tuning are crucial for improving model accuracy. 🔧
- Visualizations provide a deep understanding of the data and help identify important patterns and relationships. 📊
- This project demonstrates the utility of machine learning in predicting movie gross income, offering a valuable tool for the film industry. 🎥💡

## 📬 Contact
- For any inquiries or suggestions, you can contact me at:
   - Email 📧: jotaduranbon@gmail.com

