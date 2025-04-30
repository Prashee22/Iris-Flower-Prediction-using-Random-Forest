
# 🌸 Iris Flower Classification using Random Forest

This project implements a machine learning model to classify iris flower species using the classic Iris dataset. The goal is to predict the species of a flower (Setosa, Versicolor, Virginica) based on the length and width of petals and sepals.

---

## 📁 Dataset

The Iris dataset is loaded directly using `sklearn.datasets.load_iris()`.  
It includes:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (Target)

---

## ⚙️ Workflow

1. **Load Dataset**  
2. **Data Exploration & Visualization**  
   - Pairplots & scatter plots using seaborn and matplotlib  
3. **Preprocessing**
   - Mapping target classes to species names  
4. **Train/Test Split** (80% training, 20% testing)  
5. **Model Training**  
   - Random Forest Classifier  
   - Hyperparameter tuning (e.g., `n_estimators`, `max_depth`)  
6. **Evaluation**
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  
   - Feature Importance Plot  

---

## 🧪 Model Performance

**Random Forest Classifier**
- Accuracy: ~0.97 (example)
- Strong classification report and confusion matrix for each class

---

## 🧰 Tools & Libraries

- Python 3
- pandas
- seaborn
- matplotlib
- scikit-learn

---

## 🚀 Future Enhancements

- Try additional models (e.g., SVM, KNN)
- Use cross-validation for better robustness
- Add a Streamlit or Gradio-based interactive web interface

---

## 📜 License

This project is open source under the [MIT License](LICENSE).

---

## 🙌 Contributions

Feel free to fork this repo, open issues, or submit pull requests!
