# Hybrid Recommender System with LightFM

## 📌 Overview
This project implements a **Hybrid Recommender System** using [LightFM](https://github.com/lyst/lightfm), a Python library for building recommendation models. The system combines collaborative and content-based filtering to provide personalized recommendations.

## 🚀 Features
- **Hybrid Model:** Utilizes both user-item interactions and metadata to enhance recommendations.
- **Efficient Training:** Optimized with Stochastic Gradient Descent (SGD) and Alternating Least Squares (ALS).
- **Cold-Start Handling:** Incorporates item and user features to improve recommendations for new users/items.
- **Evaluation Metrics:** Includes precision, recall, and AUC to measure model performance.

## 📂 Project Structure
```
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks for exploration
├── src/
│   ├── preprocess.py    # Data preprocessing script
│   ├── train.py         # Model training script
│   ├── recommend.py     # Recommendation generation script
├── README.md            # Project documentation
├── requirements.txt     # Dependencies
```

## 📊 Dataset
The system is trained on a dataset containing:
- **User-item interactions** (ratings, purchases, etc.)
- **Item metadata** (categories, descriptions, etc.)
- **User metadata** (demographics, preferences, etc.)

## 🛠 Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/your-username/hybrid-recommender.git
cd hybrid-recommender
pip install -r requirements.txt
```

## 🚴 Usage
### 1️⃣ Preprocess Data
```bash
python src/preprocess.py
```
### 2️⃣ Train the Model
```bash
python src/train.py
```
### 3️⃣ Generate Recommendations
```bash
python src/recommend.py --user_id 123
```

## 📈 Evaluation
Run evaluation metrics:
```bash
python src/evaluate.py
```

## 🏗️ Future Improvements
- Implement advanced hybrid techniques (e.g., deep learning-based hybrid models)
- Optimize hyperparameters using Bayesian search
- Deploy as an API for real-time recommendations

## 📜 License
MIT License.

## 🤝 Contributing
Pull requests are welcome! If you'd like to contribute, please open an issue first to discuss the changes.

## 📬 Contact
For any inquiries, reach out at [amber.p.hou@gmail.com](mailto:amber.p.hou@gmail.com).
