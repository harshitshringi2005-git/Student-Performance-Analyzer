# 🎓 Student Performance Analyzer

> **A machine learning-powered web application that analyzes and predicts student academic performance using previous grades, attendance, and study hours.**

The **Student Performance Analyzer (STA)** is a Python and Flask-based web application that combines **Data Analysis, Machine Learning, and Data Visualization** to provide data-driven insights into student academic performance.

The application provides separate interfaces for **students and faculty**, while the machine learning component uses a **Random Forest Regressor** to predict student performance based on relevant academic factors.

---

## 🧠 About the Project

Student academic performance can be influenced by multiple factors such as previous grades, attendance, and study habits.

This project aims to use these factors to build a simple machine learning-based prediction system that can:

* Analyze academic performance data
* Identify relationships between different performance factors
* Predict expected student scores
* Track performance across subjects
* Provide faculty with performance insights

The project demonstrates how **Machine Learning and Data Science concepts can be integrated into a functional web application**.

---

## 👨‍💻 My Contribution

I contributed primarily to the **Python, Data Analysis, Machine Learning, ML Model Development, and Data Visualization** components of the project.

### Key Contributions

#### 🐍 Python Development

* Worked with Python for data processing and machine learning implementation
* Supported application functionality using Python
* Worked with Python-based ML and data analysis workflows

#### 📊 Data Analysis

* Analyzed student academic performance data
* Explored relationships between:

  * Previous grades
  * Attendance
  * Study hours
  * Academic performance
* Identified patterns and factors that may influence student results

#### 🧹 Data Preprocessing & Exploration

* Worked with student performance datasets
* Prepared data for machine learning
* Performed exploratory data analysis (EDA)
* Examined trends and relationships within the dataset

#### 🤖 Machine Learning

* Worked on machine learning-based student performance prediction
* Used **Scikit-learn** for model development
* Applied regression-based prediction techniques

#### 🌲 ML Model Development

* Worked with the **Random Forest Regressor**
* Used relevant academic features for prediction
* Supported model evaluation and prediction analysis

#### 📈 Data Visualization

* Created and worked with visual representations of academic data
* Used visualization techniques to identify trends and relationships
* Worked with **Matplotlib** and **Chart.js**

---

## 🚀 Key Features

### 👨‍🎓 Student Module

Students can:

* Register and create a profile
* Enroll in subjects
* Enter academic performance information
* Provide previous grades
* Enter attendance information
* Enter study hours
* Generate predicted scores
* Track performance across subjects
* View performance analytics

### 👨‍🏫 Faculty Module

Faculty members can:

* Register and create a profile
* Manage subjects
* View registered students
* Access student performance information
* Analyze individual student performance
* View available performance analytics
* Identify academic performance patterns

### 🤖 Machine Learning Prediction

The ML component:

* Uses previous grades as a prediction feature
* Uses attendance information
* Uses study hours
* Applies a Random Forest Regressor
* Generates predicted student scores
* Supports data-driven performance analysis

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────────┐
                    │      Web Interface      │
                    │   Student / Faculty     │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │      Flask Backend      │
                    │     Authentication      │
                    │     Application Logic   │
                    └────────────┬────────────┘
                                 │
                 ┌───────────────┴───────────────┐
                 │                               │
                 ▼                               ▼
       ┌──────────────────┐            ┌──────────────────┐
       │ Student Data     │            │ Faculty / Subject│
       │ & Performance    │            │ Management       │
       └────────┬─────────┘            └──────────────────┘
                │
                ▼
       ┌──────────────────┐
       │ Data Processing  │
       │ & Preprocessing  │
       └────────┬─────────┘
                │
                ▼
       ┌──────────────────┐
       │ Random Forest    │
       │ Regressor        │
       └────────┬─────────┘
                │
                ▼
       ┌──────────────────┐
       │ Predicted Score  │
       │ & Analytics      │
       └──────────────────┘
```

---

## 🔄 Machine Learning Workflow

The project follows an end-to-end machine learning workflow:

```text
Student Performance Data
          │
          ▼
   Data Collection
          │
          ▼
  Data Preprocessing
          │
          ▼
 Exploratory Data Analysis
          │
          ▼
   Feature Selection
          │
          ▼
 Model Training
          │
          ▼
Random Forest Regressor
          │
          ▼
    Prediction
          │
          ▼
Performance Analysis
          │
          ▼
    Visualization
```

---

## 🧠 Machine Learning Model

### Random Forest Regressor

The project uses a **Random Forest Regressor** for student performance prediction.

The model uses academic features such as:

```text
Previous Grades
      +
Attendance
      +
Study Hours
      ↓
Random Forest Regressor
      ↓
Predicted Student Score
```

Random Forest is an ensemble learning technique that combines predictions from multiple decision trees to produce a regression output.

---

## 📊 Data Analysis

The project uses data analysis techniques to understand how different academic factors relate to student performance.

### Factors Analyzed

| Factor          | Purpose                               |
| --------------- | ------------------------------------- |
| Previous Grades | Represents prior academic performance |
| Attendance      | Represents classroom participation    |
| Study Hours     | Represents time spent studying        |
| Predicted Score | Model-generated performance estimate  |

### Analysis Process

1. Load the student performance dataset
2. Inspect and understand the data
3. Handle required preprocessing
4. Explore relationships between variables
5. Identify relevant features
6. Prepare data for model training
7. Train the machine learning model
8. Generate predictions
9. Visualize results

---

## 📈 Data Visualization

Visualization is used to understand student performance patterns and relationships within the dataset.

The project uses:

* **Matplotlib**
* **Chart.js**

Visualizations can help analyze:

* Performance trends
* Attendance relationships
* Study-hour patterns
* Student performance comparisons
* Prediction-related insights

---

## 🗄️ Application Architecture

The application follows a modular Flask structure.

```text
Student-Performance-Analyzer/
│
├── app/
│   │
│   ├── models/
│   │   ├── user.py
│   │   └── ml_model.py
│   │
│   ├── routes/
│   │   ├── auth.py
│   │   ├── student.py
│   │   └── faculty.py
│   │
│   ├── static/
│   │   └── CSS / JavaScript / Images
│   │
│   ├── templates/
│   │   ├── student/
│   │   ├── faculty/
│   │   └── base.html
│   │
│   └── __init__.py
│
├── requirements.txt
├── run.py
└── README.md
```

---

## 🛠️ Technology Stack

### Programming

* **Python**

### Backend

* **Flask**

### Data Analysis

* **Pandas**
* **NumPy**

### Machine Learning

* **Scikit-learn**
* **Random Forest Regressor**

### Data Visualization

* **Matplotlib**
* **Chart.js**

### Database

* **SQLite**
* **SQLAlchemy**

### Frontend

* **HTML**
* **CSS**
* **Bootstrap**
* **JavaScript**

### Development

* **Git**
* **GitHub**

---

## 📁 Project Structure

```text
Student-Performance-Analyzer/
│
├── app/
│   ├── models/
│   │   ├── user.py          # Database models
│   │   └── ml_model.py      # ML prediction model
│   │
│   ├── routes/
│   │   ├── auth.py          # Authentication routes
│   │   ├── student.py       # Student routes
│   │   └── faculty.py       # Faculty routes
│   │
│   ├── static/              # CSS, JavaScript and images
│   │
│   ├── templates/
│   │   ├── student/         # Student templates
│   │   ├── faculty/         # Faculty templates
│   │   └── base.html        # Base template
│   │
│   └── __init__.py          # Flask application factory
│
├── requirements.txt         # Project dependencies
├── run.py                   # Application entry point
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/harshitshringi2005-git/Student-Performance-Analyzer.git
cd Student-Performance-Analyzer
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### macOS / Linux

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Environment Variables

Create a `.env` file in the project root:

```env
FLASK_APP=run.py
FLASK_ENV=development
SECRET_KEY=your-secret-key
DATABASE_URL=your-database-url
```

> ⚠️ **Security:** Never commit your actual `.env` file, database credentials, or secret keys to GitHub.

### 5️⃣ Run the Application

```bash
python run.py
```

### 6️⃣ Open in Browser

```text
http://127.0.0.1:5000/
```

---

## 👨‍🎓 Student Usage Flow

```text
Register
   ↓
Create Profile
   ↓
Enroll in Subject
   ↓
Enter Performance Data
   ↓
Submit Information
   ↓
ML Prediction
   ↓
View Predicted Score
   ↓
Track Performance
```

---

## 👨‍🏫 Faculty Usage Flow

```text
Register / Login
      ↓
Faculty Dashboard
      ↓
Manage Subjects
      ↓
View Registered Students
      ↓
View Performance Data
      ↓
Analyze Student Performance
      ↓
View Available Insights
```

---

## 🧪 Example Prediction

A student provides:

```text
Previous Grade : 78
Attendance     : 88%
Study Hours    : 4 hours/day
```

The relevant features are passed to the trained machine learning model:

```text
Previous Grade
       +
Attendance
       +
Study Hours
       ↓
Random Forest Regressor
       ↓
Predicted Score
```

> The prediction is an ML-based estimate and should be treated as an analytical aid rather than a guaranteed academic outcome.

---

## 🎯 Skills Demonstrated

This project demonstrates practical experience in:

* 🐍 Python Programming
* 📊 Data Analysis
* 🧹 Data Preprocessing
* 🔎 Exploratory Data Analysis
* 🤖 Machine Learning
* 🌲 Random Forest
* 📈 Regression
* 🧪 Model Evaluation
* 📊 Data Visualization
* 🌐 Flask Web Development
* 🗄️ SQLAlchemy
* 🗃️ SQLite
* 🔗 Git & GitHub

### Technical Workflow

```text
Python
  ↓
Data Processing
  ↓
EDA
  ↓
Feature Selection
  ↓
Machine Learning
  ↓
Random Forest Regression
  ↓
Prediction
  ↓
Data Visualization
  ↓
Web Application
```

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Working with structured academic datasets
* Performing data analysis and EDA
* Preparing data for machine learning
* Understanding regression-based prediction
* Working with Random Forest models
* Evaluating machine learning predictions
* Understanding relationships between input features and predictions
* Creating meaningful data visualizations
* Integrating ML functionality into a Flask application
* Working with databases through SQLAlchemy
* Collaborating using Git and GitHub

---

## 🔮 Future Improvements

Potential improvements include:

* 📊 Larger and more diverse datasets
* 🤖 Comparison of multiple ML algorithms
* ⚙️ Feature engineering for improved predictions
* 📈 Advanced performance dashboards
* 📑 Detailed student performance reports
* 🔐 Improved authentication and security
* 🗄️ Migration from SQLite to PostgreSQL
* 🔄 Automated model retraining
* 📊 Model performance monitoring
* 🎨 Improved user interface and user experience

---

## 🤝 Collaboration

This project was developed collaboratively.

My primary contribution focused on:

**Python Development • Data Analysis • Data Preprocessing • Machine Learning • ML Model Development • Data Visualization**

The project provided practical experience in applying **Data Science and Machine Learning concepts to a real-world-style academic performance prediction problem**.

---

## 📌 Project Information

| Category                 | Details                                     |
| ------------------------ | ------------------------------------------- |
| **Project Name**         | Student Performance Analyzer                |
| **Short Name**           | STA                                         |
| **Version**              | 1.0.0                                       |
| **Project Type**         | Machine Learning Web Application            |
| **Programming Language** | Python                                      |
| **Backend**              | Flask                                       |
| **ML Algorithm**         | Random Forest Regressor                     |
| **Database**             | SQLite                                      |
| **Purpose**              | Student performance prediction and analysis |

---

## 👨‍💻 Author

**Harshit Shringi**

B.Tech Computer Science

Interested in:

**Python • Data Science • Machine Learning • Generative AI • AI/ML Applications**

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=harshitshringi2005-git&show_icons=true&include_all_commits=true&count_private=true&hide_border=true" height="180"/>
  <img src="https://streak-stats.demolab.com/?user=harshitshringi2005-git&hide_border=true" height="180"/>
</p>

---

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐.

---

<div align="center">

### 🎓 Data Science × Machine Learning × Web Development

**Built with Python, Flask, Scikit-learn, Pandas, NumPy & Matplotlib**

</div>

---

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## 🙏 Acknowledgments

* **Flask** for the web application framework
* **Scikit-learn** for machine learning
* **Pandas & NumPy** for data processing
* **Matplotlib & Chart.js** for data visualization
* **Bootstrap** for frontend styling
