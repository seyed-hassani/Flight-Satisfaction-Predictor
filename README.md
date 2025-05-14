# ✈️ Airline Passenger Satisfaction Prediction

This project focuses on predicting airline passenger satisfaction based on various features related to the flight experience, service quality, and passenger demographics. The model is trained using a deep neural network implemented in Keras.

---

## 📁 Dataset Overview

The dataset includes two files:

- `train.csv`: Contains labeled training samples including the target column `satisfaction`.
- `test.csv`: Contains unlabeled test samples. Your model should predict the `satisfaction` column for these.

### 🧾 Features

| Feature                              | Description                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------|
| `Gender`                             | Gender of the passenger                                                    |
| `Customer Type`                      | Type of customer (e.g., loyal, disloyal)                                   |
| `Age`                                | Age of the passenger                                                       |
| `Type of Travel`                     | Purpose of travel (Business or Personal)                                   |
| `Class`                              | Flight class (Eco, Eco Plus, Business)                                     |
| `Flight Distance`                    | Distance of the flight                                                     |
| `Inflight wifi service`              | Satisfaction with in-flight wifi (1–5, 0 = no opinion)                     |
| `Departure/Arrival time convenient`  | Satisfaction with timing (1–5, 0 = no opinion)                             |
| `Ease of Online booking`             | Satisfaction with online booking (1–5, 0 = no opinion)                     |
| `Gate location`                      | Satisfaction with gate location (1–5, 0 = no opinion)                      |
| `Food and drink`                     | Satisfaction with food and drink (1–5, 0 = no opinion)                     |
| `Online boarding`                    | Satisfaction with online boarding (1–5, 0 = no opinion)                    |
| `Seat comfort`                       | Satisfaction with seat comfort (1–5, 0 = no opinion)                       |
| `Inflight entertainment`            | Satisfaction with in-flight entertainment (1–5, 0 = no opinion)            |
| `On-board service`                   | Satisfaction with onboard service (1–5, 0 = no opinion)                    |
| `Leg room service`                   | Satisfaction with legroom (1–5, 0 = no opinion)                            |
| `Baggage handling`                   | Satisfaction with baggage handling (1–5, 0 = no opinion)                   |
| `Checkin service`                    | Satisfaction with check-in (1–5, 0 = no opinion)                           |
| `Inflight service`                   | Satisfaction with general inflight service (1–5, 0 = no opinion)           |
| `Cleanliness`                        | Satisfaction with aircraft cleanliness (1–5, 0 = no opinion)               |
| `Departure Delay in Minutes`         | Delay before departure in minutes                                          |
| `Arrival Delay in Minutes`           | Delay on arrival in minutes                                                |
| `satisfaction` (target)              | Target variable: `satisfied` or `neutral or dissatisfied`                  |

---

## 🚀 Project Structure

Airline-Passenger-Satisfaction/
│
├── train.csv
├── test.csv
├── model.py
├── predict.py
├── processed_data/
├── submission.csv
└── README.md


---

## 🧠 Model

- Deep Neural Network (Keras with TensorFlow backend)
- Binary classification task
- Includes preprocessing: normalization, categorical encoding, and missing value handling

---

## 🛠️ How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Airline-Passenger-Satisfaction.git
   cd Airline-Passenger-Satisfaction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Train the model:

bash
Copy
Edit
python model.py
Generate predictions for test set:

bash
Copy
Edit
python predict.py
📊 Evaluation
The model is evaluated using:

✅ Accuracy

✅ Precision, Recall, F1-Score

✅ Confusion Matrix

✅ (Optional) ROC-AUC Curve

📜 License
This project is licensed under the MIT License.

👤 Author
Seyed Mohammad Mehdi Hassani Najafabadi
Master’s in Software Development – McMaster University
GitHub • LinkedIn
