## Personalized-Medicare ##

This Streamlit application allows users to input symptoms and receive a predicted diagnosis based on a pre-trained Support Vector Classifier (SVC) model. Additionally, the app provides useful information such as disease description, precautions, medications, recommended diets, and workouts.

## Features
- **Symptom Input**: Users can select symptoms from a predefined list.
- **Disease Prediction**: Based on the symptoms, the app predicts the most likely disease.
- **Detailed Information**: The app provides detailed information about the disease, including description, precautions, medications, diets, and workouts.

## How It Works
1. Select your symptoms from the list.
2. The app will predict the most likely disease based on the selected symptoms.
3. You will receive additional information about the disease.

## Installation
To run this application locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ayku686/Medico.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```


## Dataset
The datasets used in this application include:
- `symptoms.csv`
- `precautions.csv`
- `workouts.csv`
- `descriptions.csv`
- `medications.csv`
- `diets.csv`

These datasets contain information related to symptoms, precautions, workouts, disease descriptions, medications, and diets.

## Model
The model used for disease prediction is a pre-trained Support Vector Classifier (SVC). The model is loaded from a `svc.pkl` file.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome all contributions!

## Contact
For any questions or inquiries, please reach out to ayushkkumar123@gmail.com.
