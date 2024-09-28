# Epileptic-Seizure-Recognition-Using-Machine-Learning

## Epileptic Seizure Recognition: Evaluating Classification Modeles
This project aims to classify different states of brain activity using EEG signal data, with a specific focus on identifying epileptic seizures. Multiple machine learning models were evaluated to determine the most effective classifier for this task, including Logistic Regression, Random Forest, and Support Vector Classifier (SVC).

## Dataset
The dataset used for this project consists of EEG signals recorded from patients with different states of brain activity. The classes within the dataset include:
1. Normal Brain Activity
2. Pre-seizure Activity
3. Seizure Activity
4. Post-seizure State
5. Other Abnormal States

## Installation
To run this project locally, ensure you have Python installed along with the necessary dependencies. You can install the required libraries using:

```bash
pip install -r requirements.txt
```

## Usage
1. **Data Preprocessing**: Run the `data_preprocessing.py` script to clean and preprocess the dataset for modeling.
2. **Model Training**: Use the `model_training.py` script to train the models (Logistic Regression, Random Forest, and SVC).
3. **Model Evaluation**: Evaluate the models using the `model_evaluation.py` script or by inspecting the results in the provided notebooks.

## Models Evaluated
- **Logistic Regression**: A baseline linear model used for binary classification tasks. 
- **Random Forest Classifier**: An ensemble learning method based on decision trees.
- **Support Vector Classifier (SVC)**: A popular classification algorithm that works well with both linear and non-linear data.

## Key Insights
The project explored how well these models perform in identifying seizure and non-seizure events. The Random Forest model showed the best overall performance, while SVC and Logistic Regression provided moderate results with lower accuracy. The precision, recall, and F1-score metrics across different classes helped identify areas where each model struggles or excels, such as distinguishing between seizure and post-seizure states.

## Contributing
Contributions to the project are welcome! Feel free to fork the repository and submit a pull request with any improvements or new features.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
