# Neural Network Predicting Chances of Admission at UCLA 
 
# 🎓 Neural Network for UCLA Admission Prediction

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)

A deep learning model that predicts graduate admission chances at UCLA based on academic profiles.

## 📌 Features

- **Comprehensive Input Analysis**:
  - GRE Scores evaluation
  - TOEFL Scores assessment
  - University Rating consideration
  - SOP/LOR strength analysis
  - Undergraduate GPA evaluation
  - Research experience factor

- **Advanced Modeling**:
  - Data normalization and preprocessing
  - Feed-forward neural network architecture
  - Multiple performance metrics evaluation
 
 ## 🌐 Web Application

Check out the deployed application to predict graduate admission chances:
(https://neural-network-myn4lrfyiijv2kgs3dp5d7.streamlit.app/)

## 📂 Dataset

The dataset contains:
- 500+ student records
- 7 key admission factors
- Normalized scores (1-100 scale)

Sample features: 
GRE Score | TOEFL Score | University Rating | SOP | LOR | CGPA | Research | Chance of Admit


## 🛠️ Installation

### Prerequisites
- Python 3.8+
- pip package manager

### Setup
```bash
git clone https://github.com/Tanvir02-dev/Neural-Network.git
cd Neural-Network
pip install -r requirements.txt

🚀 Usage

python train.py \
  --data_path data/admission_data.csv \
  --epochs 100 \
  --batch_size 32

Making Predictions
python predict.py --input data/sample_input.csv

GRE Score,TOEFL Score,University Rating,SOP,LOR,CGPA,Research
337,118,4,4.5,4.5,9.65,1

🧠 Model Architecture
Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense_1 (Dense)              (None, 64)                512       
_________________________________________________________________
dropout_1 (Dropout)          (None, 64)                0         
_________________________________________________________________
dense_2 (Dense)              (None, 32)                2080      
_________________________________________________________________
dense_3 (Dense)              (None, 1)                 33        
=================================================================
Total params: 2,625
Trainable params: 2,625
Non-trainable params: 0

📊 Performance Metrics
Metric	Training	Validation
MAE	0.015	0.018
R² Score	0.92	0.89
Accuracy	87%	85%

🌟 Future Enhancements
Hyperparameter tuning with Optuna
Web application integration
Additional feature engineering
Real-time prediction API

🤝 Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some amazing feature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📜 License
Distributed under the MIT License. See LICENSE for more information.

📧 Contact
Tanvir Singh - ssahej990@gmail..com

Project Link: https://github.com/Tanvir02-dev/Neural-Network


