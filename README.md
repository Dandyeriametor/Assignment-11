# Assignment-11
Image Classification Using Random Forest
# Image Classification with Random Forest and SVM

This project implements an end-to-end image classification system using traditional machine learning models—Random Forest and Support Vector Machine (SVM). The workflow includes image preprocessing, feature extraction, model training, hyperparameter tuning, evaluation, and prediction on new images.

##  Project Structure
- **notebook.ipynb** — Google Colab notebook containing the full implementation  
- **report.pdf / .docx** — 2-page project report  
- **images/** — Dataset (not included; user must supply their own)  

##  Features
- Loads and preprocesses images (resize, normalize, flatten)  
- Hyperparameter tuning with `GridSearchCV`  
- Random Forest + SVM model comparison  
- Confusion matrix & classification report  
- Feature importance visualization  
- Function for predicting new images  

## Requirements
- Python 3.x  
- NumPy, Pandas  
- scikit-learn  
- Matplotlib  
- Pillow  

Install dependencies:
```bash
pip install numpy pandas scikit-learn matplotlib pillow
