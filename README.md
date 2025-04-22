Book Genre Classification
This project classifies books into genres using a Random Forest Classifier based on features like author popularity, book length, and the number of keywords.

Features:
Author Popularity: Numerical representation of author popularity.

Book Length: Length of the book (pages or word count).

Number of Keywords: Number of keywords associated with the book.

Genre: The target genre we want to predict (e.g., Fiction, Non-Fiction).

Steps:
Data Loading: Load dataset from CSV.

Preprocessing: Encode the target genre using LabelEncoder.

Train-Test Split: Split the data into 80% training and 20% testing.

Model Building: Train a Random Forest Classifier on the training data.

Evaluation: Calculate Accuracy, Precision, Recall, and F1 Score. Generate a Confusion Matrix.

Visualization: Plot a heatmap of the confusion matrix.

Libraries:
Pandas: Data handling.

Scikit-learn: Machine learning.

Seaborn & Matplotlib: Visualization.

How to Run:
Install required libraries:

bash
Copy
Edit
pip install pandas scikit-learn seaborn matplotlib
Download the dataset as book_genres.csv.

Run the Python script to train and evaluate the model.

Results:
The model's performance is evaluated with accuracy, precision, recall, and F1 score.

A confusion matrix heatmap is displayed for visual evaluation.

