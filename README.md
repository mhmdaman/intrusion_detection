Intrusion Detection System using Deep Learning

Overview

This project implements a Network Intrusion Detection System (IDS) using deep learning techniques on the UNSW-NB15 dataset. The notebook performs dataset downloading, preprocessing, training, and evaluation of a machine learning model for detecting malicious network traffic.

The project is built and executed in entity[“software”,“Google Colab”,“Google Colaboratory notebook platform”] using Python, TensorFlow, and common data science libraries.

⸻

Features

* Automatic dataset download using Kaggle API
* Extraction and preprocessing of the UNSW-NB15 dataset
* Data cleaning and preparation
* Deep learning model training using TensorFlow/Keras
* Evaluation of model performance
* Detection of normal and attack network traffic

⸻

Dataset

This project uses the UNSW-NB15 intrusion detection dataset.

Dataset source:

urlUNSW-NB15 Dataset on Kagglehttps://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15

⸻

Technologies Used

* Python
* TensorFlow
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Kaggle API
* Google Colab

⸻

Project Workflow

1. Install required libraries
2. Configure Kaggle API
3. Download the UNSW-NB15 dataset
4. Extract dataset files
5. Load train and test CSV files
6. Preprocess and clean data
7. Train deep learning model
8. Evaluate model accuracy
9. Predict intrusion attacks

⸻

Installation

Clone the Repository

git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name

Install Dependencies

pip install tensorflow pandas numpy scikit-learn matplotlib kaggle

⸻

Kaggle API Setup

1. Go to your Kaggle account settings.
2. Generate a new API token.
3. Download the kaggle.json file.
4. Upload it when prompted in the notebook.

⸻

Running the Notebook

Open the notebook in Google Colab or Jupyter Notebook:

jupyter notebook intrusiondetection_py.ipynb

or upload the notebook directly to Google Colab.

⸻

Example Output

The model classifies network traffic as:

* Normal
* Intrusion / Attack

Evaluation metrics may include:

* Accuracy
* Precision
* Recall
* Confusion Matrix

⸻

Folder Structure

project-folder/
│
├── intrusiondetection_py.ipynb
├── README.md
└── unsw_data/

⸻

Future Improvements

* Add real-time intrusion detection
* Deploy as a web application
* Improve model accuracy using advanced architectures
* Add visualization dashboards
* Support additional datasets

⸻

Author

Muhammed Aman

⸻

License

This project is for educational and research purposes.
