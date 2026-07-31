# AI-Based Cancer Detection and Survival Prediction

## Live Demo

Try the deployed application here:

https://ai-based-cancerdetection-and-survival-prediction-7xm2d64sb6d6s.streamlit.app/

## Project Overview
This project is an AI-powered healthcare application developed to assist in cancer detection and survival prediction using Deep Learning and Machine Learning techniques.
The system analyzes medical images to detect abnormalities, classify cancer type, and predict cancer stage and 5-year survival probability using clinical data. A user-friendly Streamlit web application provides an interactive interface for making predictions.

> **Note:** This project is developed for educational purposes only and should not be used for real-world medical diagnosis.

## Features

- Normal vs Abnormal tissue detection
- Breast Cancer vs Lung Cancer classification
- Benign vs Malignant prediction (Breast Cancer)
- Cancer stage prediction using clinical data
- 5-year survival prediction
- Interactive Streamlit web application
- Easy-to-use interface for image upload and prediction

## Technologies Used

- Python
- Streamlit
- TensorFlow / Keras
- Scikit-learn
- XGBoost
- OpenCV
- Pandas
- NumPy
- Matplotlib
- Pillow

## Project Workflow

1. Upload a medical image.
2. Detect whether the image is **Normal** or **Abnormal**.
3. If abnormal, identify the cancer type (**Breast** or **Lung**).
4. For breast cancer, classify the tumor as **Benign** or **Malignant**.
5. Enter the patient's clinical details.
6. Predict the cancer stage.
7. Predict the patient's 5-year survival probability.

## Results

The system successfully performs multi-stage cancer analysis using both medical image classification and clinical data.

### Image-Based Prediction

- Normal vs Abnormal Detection
- Breast vs Lung Cancer Classification
- Benign vs Malignant Classification (Breast Cancer)

### Clinical Prediction

Using patient information such as age, tumor size, lymph node count, and metastasis status, the system predicts:
- Cancer Stage
- 5-Year Survival Probability

### Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Future Scope

- Improve prediction accuracy using larger clinical datasets.
- Add support for additional cancer types.
- Generate downloadable medical reports.
- Enhance the user interface.
- Integrate with hospital information systems.

## How to Run the Project

1. Clone this repository.

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Run the Streamlit application.

```bash
streamlit run scripts/streamlit.py
```

4. Open the local URL displayed in your browser.

## Download Trained Models

The trained models are too large for GitHub, so they are stored in Google Drive.

### Stage 1 - Normal vs Abnormal
https://drive.google.com/file/d/1D7oYw_PGK6QPhjxxEgcgUgCxikaDRGvV/view?usp=drive_link

### Stage 2 - Cancer Type
https://drive.google.com/file/d/1fDLrFd8t3TYSz60FTVGTBfYfUhW0yPR5/view?usp=drive_link

### Breast Stage Model
https://drive.google.com/file/d/14wcU_3CY4Hfok32fZkRk51WKgJ8fF7xO/view?usp=drive_link

After downloading, place the `.h5` files inside the `models/` folder.
