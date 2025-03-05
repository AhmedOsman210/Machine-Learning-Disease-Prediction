# Machine Learning Disease Prediction

A machine learning project that predicts diseases based on given symptoms. This project uses classification algorithms such as Random Forest, Naive Bayes, and Support Vector Classifier (SVC) to predict the disease based on input symptoms.
![Random Forest Classifier](random_forest_classifier.png)
![Correlation Heatmap](correlation_heatmap.png)

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project aims to build a predictive model for disease diagnosis based on input symptoms. We utilize multiple classification models (Random Forest, Naive Bayes, and Support Vector Classifier) and evaluate their performance using accuracy, confusion matrices, and other metrics.

The project also explores feature importance, correlation analysis, and ensemble methods for a comprehensive approach to disease prediction.

## Features

- **Multiple Models**: The project includes SVC, Naive Bayes, and Random Forest models.
- **Data Preprocessing**: Clean and scale data for better performance.
- **Ensemble Method**: Combine model predictions using a majority vote.
- **Confusion Matrix**: Visualizes model performance.
- **Model Evaluation**: Calculate accuracy, precision, recall, and F1-score.

## Technologies Used

- **Python** (for the overall coding and implementation)
- **Scikit-learn** (for machine learning models and metrics)
- **Pandas** (for data manipulation)
- **NumPy** (for numerical computations)
- **Matplotlib** and **Seaborn** (for data visualization)
- **Jupyter Notebook** (for the interactive environment)

## Installation Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/disease-prediction.git
   cd disease-prediction
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
This will install all the required libraries like scikit-learn, numpy, matplotlib, etc.

Usage
Run the Jupyter notebook: You can open the disease_prediction.ipynb file to explore the project in a notebook environment.

bash
Copy
Edit
jupyter notebook disease_prediction.ipynb
Input Symptoms: Once the model is trained, provide symptoms as input, and it will predict the disease label.

Model Evaluation: The confusion matrix, classification report, and accuracy score will be displayed after model evaluation.

Visualization:

Random Forest Classifier: Displays feature importance.
Correlation Heatmap: Displays the correlation between features.
Results
After training and testing, the following results were obtained for the Random Forest model:

Accuracy: 85.6%
Precision: 0.89
Recall: 0.83
F1-score: 0.86
Visualizations
Correlation Heatmap: Shows the relationships between different symptoms/features.


Random Forest Classifier Feature Importance: Displays the importance of each feature in the Random Forest model.


Contributing
Contributions are welcome! If you want to contribute, please follow the steps below:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature-name).
Make your changes and commit (git commit -am 'Add new feature').
Push to your branch (git push origin feature/your-feature-name).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

markdown
Copy
Edit

### How to Upload and Use the Images:

1. **Add the Images to Your Repository**:
   - Create a folder named `images` in your project directory.
   - Upload the `random_forest_classifier.png` and `correlation_heatmap.png` images into this folder.
   
2. **Link the Images in Your README**:
   - In the markdown code above, the images are linked as `images/random_forest_classifier.png` and `images/correlation_heatmap.png`, which are relative paths that point to the images inside your repository.

3. **Push Your Changes**:
   - Once you’ve added the images and updated the README, push the changes to GitHub.

```bash
git add images/random_forest_classifier.png images/correlation_heatmap.png README.md
git commit -m "Added images and updated README"
git push origin main
Notes:
Make sure the image files are correctly uploaded into the images folder in your repository.
If you're hosting the images elsewhere (e.g., Imgur), replace the images/random_forest_classifier.png URL with the direct URL from the hosting service.
