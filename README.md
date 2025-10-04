# Applied Data Science Capstone 🚀

This repository contains the final capstone project for the IBM Data Science Professional Certificate.  
The project focuses on **SpaceX Falcon 9 Launches** and demonstrates a complete end-to-end Data Science workflow:  
from data collection, cleaning, exploratory analysis, and visualization to predictive modeling and interactive dashboard deployment.

---

## 📂 Project Structure
```
Applied-Data-Science-Capstone/
│
├── notebooks/              # Jupyter notebooks for each stage of analysis
│   ├── spacex_data_wrangling.ipynb
│   ├── spacex_eda.ipynb
│   ├── spacex_sql.ipynb
│   ├── spacex_ml_models.ipynb
│   └── spacex_dashboard.ipynb
│
├── data/                   # Datasets (CSV, SQLite DB)
│   ├── spacex_launches.csv
│   └── spacex.db
│
├── spacex-dash-app.py      # Interactive Dash web application
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
```

---

## 🎯 Objectives
- Collect and preprocess SpaceX launch data from APIs and web sources.  
- Perform **Exploratory Data Analysis (EDA)** to identify factors influencing Falcon 9 first stage landing success.  
- Apply **SQL queries** for data analysis.  
- Build and compare several **Machine Learning models** (Logistic Regression, SVM, Decision Tree, KNN).  
- Develop an interactive **Dashboard using Dash** for visualizing results.  

---

## 📊 Key Insights
- The success of Falcon 9 landings strongly correlates with **launch site**, **payload mass**, and **orbit type**.  
- Logistic Regression and Decision Tree models performed best in predicting landing success.  
- Visualization with Folium maps highlighted geographic clustering of launch sites.  

*(Replace with your actual results, graphs, or metrics — e.g. model accuracy, precision, recall, etc.)*

---

## ⚙️ Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/samanmoh1989/Applied-Data-Science-Capstone.git
   cd Applied-Data-Science-Capstone
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebooks for analysis:
   ```bash
   jupyter notebook
   ```

4. Launch the dashboard app:
   ```bash
   python spacex-dash-app.py
   ```
   The app will run locally at `http://127.0.0.1:8050/`.

---

## 🖼️ Demo
👉 *(Add screenshots or GIF of your dashboard and sample outputs here)*  
👉 *(If deployed on Render/Railway/Heroku, add the live demo link here)*  

---

## 📚 Tech Stack
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn, plotly, folium)  
- **SQL** (SQLite)  
- **Dash & Plotly** for interactive dashboard  
- **Jupyter Notebook** for experimentation and analysis  

---

## 📌 Future Improvements
- Experiment with ensemble ML models (Random Forest, Gradient Boosting).  
- Automate data collection via API pipelines.  
- Deploy the dashboard on a cloud service for public access.  

---

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.  
