# 🌾 Crop Recommendation System
DS sem6-Microproject

Efficient crop selection is crucial for maximizing yield, ensuring sustainability, and improving farmer profitability. This project uses a Random Forest machine learning model to recommend the most suitable crop based on soil and environmental parameters like NPK levels, pH, temperature, humidity, and rainfall. By leveraging data-driven insights, it aims to support smarter, more sustainable agricultural practices.

---

## 📌 Features

- Input parameters: **Nitrogen (N)**, **Phosphorus (P)**, **Potassium (K)**, **Temperature**, **Humidity**, **pH**, **Rainfall**
- Predicts crop using trained **Random Forest Classifier**
- Clean and responsive web interface using **Flask + HTML/CSS**
- Real-time prediction powered by a pre-trained model saved as `model.pkl`

---

## 🧠 Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: Python (Flask)
- **ML Algorithm**: Random Forest Classifier
- **Libraries**: pandas, scikit-learn, pickle, Flask, seaborn, matplotlib

---

## ⚙️ Prerequisites

Make sure you have the following installed on your machine:

- **Python 3.7 or higher**
- **pip (Python package installer)**


```bash
# 1. Clone the repository
git clone https://github.com/yourusername/crop-recommendation-system.git
cd crop-recommendation-system

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate        # For Linux or Mac
# venv\Scripts\activate         # For Windows

# 3. Install required dependencies
pip install flask pandas scikit-learn matplotlib seaborn
