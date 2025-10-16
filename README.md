Music Genre Predictor (Machine Learning)

This project is a simple machine learning program that predicts a person’s preferred music genre based on their age using a Decision Tree Classifier from Scikit-learn.

🚀 Overview

The Music Genre Predictor demonstrates how an ML model can learn from example data and make predictions on new inputs.
It uses a small dataset mapping different age groups to their likely music preferences (e.g., teens → Pop, adults → Rock, seniors → Jazz).

🧠 Technologies Used

Python 3

scikit-learn (for machine learning)

NumPy (for numerical operations)

📂 How It Works

Dataset Creation:
A simple dataset of ages and corresponding genres is created manually.

Model Training:
A DecisionTreeClassifier is trained on this dataset.

Prediction:
The model predicts music genres for test ages and user-input ages.

Evaluation:
Displays the model’s training accuracy and a note about real-world improvement.

🎧 Example Output
Welcome to the Music Genre Predictor!
==================================================

Training the model with sample data...
Model trained successfully!
The model has learned patterns from 24 examples

==================================================
Let's predict some music preferences!
==================================================

Age 17 -> Predicted Genre: Hip-Hop
Age 25 -> Predicted Genre: Rock
Age 35 -> Predicted Genre: Rock
Age 55 -> Predicted Genre: Classic Rock
Age 68 -> Predicted Genre: Jazz

💡 Features

✅ User-friendly console interface
✅ Real-time user input for predictions
✅ Easy to understand for ML beginners
✅ Explains model training and evaluation process

📈 Model Details

Algorithm: Decision Tree Classifier

Target Variable: Music Genre

Feature: Age

Accuracy: Displays training accuracy (for demonstration)

🔮 Future Improvements

Add more features like gender, location, or favorite artists.

Use real-world datasets for better accuracy.

Implement a web or GUI interface to make it interactive.

Compare with other algorithms like Random Forest or KNN.

🧩 Usage

Clone this repository:

git clone https://github.com/MadaraSensei-art/MusicgenrePredictorML.git


Navigate to the folder:

cd MusicgenrePredictorML


Run the script:

python music_genre_predictor.py

👤 Author

Kishore Arjunan
💻 AI & ML Enthusiast | 🎶 Exploring Data and Creativity
