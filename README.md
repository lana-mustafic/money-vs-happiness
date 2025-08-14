# Money vs Happiness Analysis 
[![Python 3.13](https://img.shields.io/badge/python-3.13-blue.svg)](https://www.python.org/downloads/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)  

An analysis exploring the relationship between GDP per capita and happiness scores using World Happiness Report data.

## **✨ Project Impact**  
This project demonstrates how data science can uncover insights about human well-being at scale. By quantifying the GDP-happiness relationship, it provides:  
- **Policy insights** for economic development strategies  
- **Benchmarking tools** for country comparisons  
- **A template** for reproducible socio-economic analysis  

---

## 📁 Repository Structure  
```
money-vs-happiness/
├── data/
│ ├── raw_data/ # Original datasets
│ └── cleaned_data.csv # Processed merged dataset
├── figures/ # Generated visualizations
│ ├── gdp_happiness_scatter.png
│ └── correlation_matrix.png # New!
├── notebooks/
│ ├── 1_data_cleaning.ipynb # Data preparation
│ └── 2_analysis.ipynb # Complete analysis
├── requirements.txt # Python dependencies
└── README.md # This file
```

## 🔍 Key Findings  
| Metric               | Value | Insight |
|----------------------|-------|---------|
| **GDP-Happiness (r)** | 0.78  | Strong positive correlation |
| **R² Score**         | 0.61  | GDP explains 61% of variance |
| **Top Country**      | Finland | 7.80/10 happiness score |
| **Key Outlier**      | Costa Rica | Higher happiness than GDP predicts |

![Analysis Preview](figures/gdp_happiness_scatter.png)

---

## 🛠️ Installation  
```bash
git clone https://github.com/your-username/money-vs-happiness.git
cd money-vs-happiness
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
```

##🚀 Usage
bash
jupyter notebook
bash
Notebook Execution Order:

1_data_cleaning.ipynb - Data preparation

2_analysis.ipynb - Complete analysis with:

Advanced visualizations

Statistical modeling

Interactive country explorer

##📊 Data Sources
World Happiness Report 2023

World Bank GDP Data

##🤝 How to Contribute
Fork the repository

Create a feature branch (git checkout -b feature/your-feature)

Commit changes (git commit -m 'Add some feature')

Push to branch (git push origin feature/your-feature)

Open a Pull Request

##📝 License
MIT License - See LICENSE for details.
