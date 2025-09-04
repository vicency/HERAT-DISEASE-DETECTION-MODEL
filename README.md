# Heart Disease Detection Model

This project is a web application that predicts heart disease using a machine learning model trained on heart disease datasets. The application is built with Streamlit, allowing users to input medical data and receive predictions about their heart health.

## Features

- **Streamlit Web App**: Simple and interactive interface for heart disease prediction.
- **Model Integration**: Uses a pre-trained machine learning model (`model.pkl`) for predictions.
- **Multiple Datasets**: Includes both classic UCI heart datasets and reformatted datasets for model training and testing.

## How It Works

1. **User Inputs**: The user enters relevant medical information including age, chest pain type, heart pain value, exercise pain, oldpeak, number of blood vessels, and blood disorder type.
2. **Prediction**: The app uses the trained model to predict if the user has heart disease.
3. **Result**: The app displays a success (No Heart Disease) or error (Heart Disease Detected) message.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vicency/HERAT-DISEASE-DETECTION-MODEL.git
   cd HERAT-DISEASE-DETECTION-MODEL
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   If `requirements.txt` is not available, install manually:
   ```bash
   pip install streamlit pandas numpy scikit-learn
   ```

3. **Run the app**:
   ```bash
   streamlit run app.py
   ```

## Files

- `app.py`: Streamlit web application for prediction.
- `model.pkl`: The serialized trained machine learning pipeline.
- `heart dataset.csv`: Raw dataset (numeric features, classic format).
- `heart diseases data.csv`: Reformatted dataset (used for categorical feature engineering).
- `m_heart.ipynb`: Jupyter notebook for data exploration, model training, and evaluation.

## Example Usage

1. Start the app with `streamlit run app.py`.
2. Fill in the requested medical information in the sidebar.
3. Click "Predict" to receive the result.

## Data Sources

- The datasets originate from the UCI Heart Disease repository and have been reformatted for use in this project.

## Model Training

The model is trained using scikit-learn on the provided datasets. Feature engineering and preprocessing steps can be found in `m_heart.ipynb`.

## Contributing

1. Fork this repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [Scikit-learn](https://scikit-learn.org/)
- [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

---
**Author:** [vicency](https://github.com/vicency)
