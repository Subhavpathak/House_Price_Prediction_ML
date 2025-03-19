## 🏡 House Price Prediction using Machine Learning

This project predicts house prices based on various features using **Random Forest Regressor**.  
It includes **data preprocessing, model training, and a Flask-based UI** for user interaction.  

---

## 📊 Dataset Information
- **Source:** [Kaggle - California Housing Prices](https://www.kaggle.com/datasets)  
- **Size:** ~20,000 samples  
- **Features Used:**
  - `longitude`, `latitude` → Geolocation  
  - `median_income`, `households` → Economic factors  
  - `total_rooms`, `total_bedrooms`, `population` → Housing stats  
  - `ocean_proximity` → Categorical feature  

---

## ⚙️ Preprocessing & Feature Engineering
- **Handled missing values** using median imputation.
- **Feature Scaling** using `StandardScaler`.
- **Categorical Encoding** using `OneHotEncoder`.
- **Log Transformations** applied for skewed distributions.

---

## 📈 Model Performance
| Model                 | Accuracy (%) |
|----------------------|-------------|
| Linear Regression   | 72.5%       |
| Decision Tree       | 79.8%       |
| Random Forest (Final Model) | **83.33%** |

---

## 🖥️ User Interface (UI)
- **Built with Flask**: Interactive web-based UI for easy predictions.
- **HTML & CSS**: Modern design for seamless user experience.

---

## 🚀 How to Run the Project
```bash
# 1️⃣ Clone the repository
git clone https://github.com/YOUR-USERNAME/house-price-prediction.git
cd house-price-prediction

# 2️⃣ Install dependencies
pip install -r requirements.txt

# 3️⃣ Run Flask app
python app.py
```

## 🖥️ UI Overview (Flask)
- ✅ User enters features (income, location, rooms, etc.).
- ✅ Model predicts house price in real-time.
- ✅ Responsive UI using Flask.

## 🔧 Future Improvements
- ✅ Improve Model: Try XGBoost for better accuracy.
- ✅ Deploy Online: Host on Render or AWS.
- ✅ Enhance UI: Make a React frontend instead of Flask.

## 🛠 Technologies Used
- ML: scikit-learn, pandas, numpy
- Backend: Flask, Gunicorn
- Frontend: HTML, CSS, Bootstrap/Tailwind
## 🏆 Contributors
- 👨‍💻 Subhav Kumar – Data Preprocessing & Flask API & Model Training 
- 👨‍💻 Kunal Kumar Shaw – UI Development using Flask
- 👨‍💻 Sonu Anand – Model Training & Performance Optimization

## 🤝 Contribution
- Feel free to contribute by forking the repository and submitting a pull request.
- 🔗 GitHub: Subhavpathak
- 📧 Contact: subhavpathak18@gmail.com

