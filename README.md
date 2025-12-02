# 🍷 Wine Quality Analysis – Data Science Project
This project explores what makes a red wine “high quality” based on its chemical properties.
The analysis was created for a food retail company interested in improving its product selection.

All work is contained in a single exploratory notebook and a short slide deck.

## 📊 Key Insights

Higher alcohol content → higher quality

Sulfates contribute positively to quality

Volatile acidity has a clear negative effect

Only ~12% of wines in the dataset are high quality

A Random Forest model reached 89% accuracy, with lower recall for the rare high-quality wines (class imbalance)

These patterns are clearly visible in the visualizations inside the notebook.

## 📊 Project Structure

notebook/ — contains the full analysis notebook (Wein_Analyse.ipynb)

reports/ — includes the slide deck and exported figures

requirements.txt — minimal dependencies to run the notebook

README.md — project documentation

## 📂 Dataset

This project uses the public Wine Quality dataset (red wine only):
🔗 https://archive.ics.uci.edu/dataset/186/wine+quality

(The raw data is not included in this repository due to licensing.)

## ▶️ How to Run

Open the notebook in Google Colab or Jupyter Notebook

Install dependencies:

pip install -r requirements.txt

Download the dataset from the link above

Run all cells in the notebook


## 🚀 Next Steps
If extended, this project could include:
- SMOTE or other solutions to address class imbalance
- Hyperparameter tuning
- Gradient boosting models
- A small API or Streamlit demo
- A comparison with white wines


## 👩‍💻 About Me
I'm Maryam - a data scientist. I studied my bachelor in computer engineering with software specialization and my masters in computer science with AI and data science specialization. I'd like to work on practical topics and use my know-how and skills in data science and storytelling to fill the gap between science and society.

Contact me via linkedin: https://www.linkedin.com/in/maryam-arabshahi-54428453/

Email: arabshahi.ma@gmail.com
