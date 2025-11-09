# 📘 Telco Churn Prediction

## 📌 Overview | معرفی کلی
This project predicts **customer churn** in a telecommunications company using **real customer data** and **machine learning models**.  
The goal is to **identify customers likely to leave** and understand **the key factors influencing churn**, helping businesses design better retention strategies.

این پروژه به پیش‌بینی **ریزش مشتریان در شرکت‌های مخابراتی** با استفاده از **داده‌های واقعی مشتریان** و مدل‌های **یادگیری ماشین** می‌پردازد.  
هدف، **شناسایی مشتریان در معرض ترک** و درک **عوامل مؤثر بر تصمیم آن‌ها** برای طراحی کمپین‌های وفادسازی مؤثر است.

---

## 📂 Dataset | داده‌ها
- **Source:** [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)  
- **Records:** 7,043 customers  
- **Features:** 21 features (demographics, services, payment details, etc.)

دیتاست از **سایت Kaggle** استخراج شده و شامل **۷۰۴۳ رکورد مشتری** و **۲۱ ویژگی** مانند اطلاعات جمعیت‌شناختی، نوع سرویس و جزئیات پرداخت است.

---

## 🛠️ Technologies Used | ابزارها و فناوری‌ها
| Category | Tools |
|-----------|--------|
| Language | Python 3 |
| Environment | Jupyter Notebook |
| Data Processing | pandas, numpy |
| Visualization | seaborn, matplotlib |
| Machine Learning | scikit-learn (RandomForestClassifier, preprocessing pipelines) |

در این پروژه از زبان **پایتون**، محیط **Jupyter** و کتابخانه‌های **pandas، numpy، matplotlib، seaborn** و **scikit-learn** برای مدل‌سازی استفاده شده است.

---

## 📁 Project Structure | ساختار پروژه
Telco-Churn-Prediction/
│
├── notebooks/
│ ├── 1_data_exploration.ipynb # Data cleaning, visualization, and EDA
│ └── 2_churn_prediction_model.ipynb # Model training and evaluation
│
├── tests/
│ └── test_imports.py # Basic test for dependency validation
│
├── requirements.txt # Python dependencies
├── pyproject.toml # Project configuration
├── README.md # Project documentation
└── LICENSE # MIT license


پروژه شامل دو نوت‌بوک برای تحلیل داده و مدل‌سازی، فایل‌های پیکربندی و تست‌ها است.

---

## 📊 Results & Insights | نتایج و تحلیل‌ها
- **Model Used:** Random Forest Classifier  
- **Accuracy:** ~80%  
- **Key Factors Influencing Churn:**  
  - Contract Type  
  - Tenure (Customer Lifetime)  
  - Monthly Charges  

مدل **Random Forest** با دقت حدود **۸۰٪** توانست مشتریان در معرض ریزش را شناسایی کند.  
ویژگی‌هایی مثل **نوع قرارداد، مدت عضویت و هزینه ماهانه** بیشترین تأثیر را داشتند.

---

## ▶️ How to Run | نحوه اجرا
To run this project locally:

```bash
# 1. Clone the repository
git clone https://github.com/shahpari2kht/Telco-Churn-Prediction.git
cd Telco-Churn-Prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open notebooks
jupyter notebook


برای اجرای پروژه:

مخزن را کلون کنید

کتابخانه‌ها را نصب کنید

فایل‌های نوت‌بوک را در محیط Jupyter اجرا کنید

🤝 Contribution | مشارکت

Contributions, bug reports, and feature suggestions are welcome.
Feel free to open an issue or submit a pull request.

هرگونه پیشنهاد، گزارش باگ یا توسعه‌ی جدید با آغوش باز پذیرفته می‌شود.

📝 License | مجوز

This project is released under the MIT License — free to use, modify, and distribute.
این پروژه تحت مجوز MIT منتشر شده و استفاده و توسعه‌ی آزاد دارد.

📬 Contact | ارتباط با من

👩‍💻 Parisa Mohammadzadeh
📧 Email: Shahpari2kht@gmail.com

🔗 LinkedIn
 | GitHub
