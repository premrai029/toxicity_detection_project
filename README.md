# toxicity_detection_project

Toxic Comment Detection and classification

Project Description
This project is a Machine Learning-based text classification system that detects toxic comments and classifies text into four categories:
- Negative  
- Neutral  
- Positive  
- Toxic  
The model is built using NLP techniques and trained with a Multinomial Naive Bayes classifier with TF-IDF feature extraction.


Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- TF-IDF Vectorization  
- Matplotlib & Seaborn  
- Joblib  

Project Files
- `minorprj.ipynb` – Main project notebook  
- `minorprj.html` – HTML export of notebook  
- `minorprj.pdf` – Project report  
- `toxicity_model.pkl` – Trained model  
- `requirements.txt` – Project dependencies  

Dataset not included due to size limitations.
You can find and download dataset from the link: https://drive.google.com/file/d/1c9ulFjPJfX5tUk1zfWnLrBE6r3n3FxIe/view?usp=sharing


Installation

```bash
pip install -r requirements.txt
```

Usage

Load the trained model:
```python
import joblib

model = joblib.load("toxicity_model.pkl")
prediction = model.predict(["Sample text"])
print(prediction)
```
