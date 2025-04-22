Book Genre Classification
This project uses machine learning to classify books into genres based on features such as author popularity, book length, and the number of keywords. It utilizes a Random Forest Classifier for predicting the genre of a book.

Features:
Author Popularity: Numerical representation of how popular the author is.

Book Length: Length of the book, likely measured in pages or word count.

Number of Keywords: Number of keywords associated with the book.

Target Variable (Genre): The genre of the book, which is the class we are predicting (e.g., Fiction, Non-Fiction).

Steps Involved:
Data Loading:

Load the dataset (book data) from a CSV file.

Data Preprocessing:

Extract features (author_popularity, book_length, num_keywords) and the target variable (genre).

Encode the categorical target variable into numeric values using LabelEncoder.

Train-Test Split:

Split the dataset into training (80%) and testing (20%) sets using train_test_split.

Model Building:

Train a Random Forest Classifier with 100 trees to predict the book genre.

Model Evaluation:

Evaluate the model's performance using metrics such as:

Accuracy

Precision

Recall

F1 Score

Compute the Confusion Matrix to visualize the performance.

Visualization:

Generate a heatmap of the confusion matrix to make it easier to interpret model results.

Libraries Used:
Pandas: For data manipulation.

Scikit-learn: For machine learning and model evaluation.

Seaborn & Matplotlib: For visualization (confusion matrix heatmap).

How to Run:
Install the required libraries:

bash
Copy
Edit
pip install pandas scikit-learn seaborn matplotlib
Download the dataset and save it as book_genres.csv.

Run the script to train the model and evaluate its performance.

Results:
The model’s performance is evaluated using accuracy, precision, recall, and F1 score.

A confusion matrix heatmap is generated to visually show how well the model predicts different genres.

