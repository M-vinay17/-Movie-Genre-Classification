# 🎬 Movie Genre Classification

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

This project aims to classify movie genres based on their plot summaries using machine learning techniques. The dataset used for this project is the IMDb Movie Dataset, which contains information about movies including their titles, genres, and plot summaries.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK / spaCy (for text preprocessing)
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook

---

## 📂 Dataset

The IMDb Movie Dataset used in this project contains the following features:

- Title: The title of the movie.
- Genre: The genre(s) of the movie.
- Plot Summary: A brief summary of the plot of the movie.

## ⚙️ Methodology

1. **Data Preprocessing**: The dataset is cleaned and preprocessed to remove any irrelevant information and handle missing values.

2. **Text Processing**: The plot summaries are tokenized, normalized, and vectorized using techniques such as TF-IDF (Term Frequency-Inverse Document Frequency).

3. **Model Building**: Various machine learning algorithms such as Naive Bayes, Logistic Regression, and Random Forest are trained on the vectorized plot summaries to classify the movies into different genres.

4. **Model Evaluation**: The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score.

5. **Hyperparameter Tuning**: The hyperparameters of the best-performing model are fine-tuned to improve its performance further.

---

## 📁 Project Structure
```
MOVIE-GENRE-CLASSIFICATION/
│-- data/                  # Dataset files
│-- notebooks/             # Jupyter notebooks for EDA & modeling
│-- models/                # Saved trained models
│-- requirements.txt       # Project dependencies
└── README.md
```

---

## 🚀 Usage

To run the code:

1. Clone the repository:
   ```
   git clone https://github.com/M-vinay17/MOVIE-GENRE-CLASSIFICATION.git
   ```

2. Navigate to the project directory:
   ```
   cd MOVIE-GENRE-CLASSIFICATION
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook or Python script to train and evaluate the models.

## 📊 Results

The best-performing model achieves an accuracy of X% on the test dataset.

---

## 🚀 Future Work

- Experiment with different text processing techniques such as word embeddings and deep learning models.
- Explore ensemble methods to further improve the classification performance.
- Enhance the dataset by incorporating additional features or external data sources.
- Deploy the model as a web app using Flask / Streamlit for interactive genre prediction.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/M-vinay17/MOVIE-GENRE-CLASSIFICATION/issues) or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Author

**M Vinay Kumar**

🎓 B.Tech – Artificial Intelligence & Machine Learning, Sri Venkateswara College of Engineering (SVCE), Tirupati

📧 Email: [mvinaykumar1786@gmail.com](mailto:mvinaykumar1786@gmail.com)  
💻 GitHub: [M-vinay17](https://github.com/M-vinay17)  
🔗 LinkedIn: [m-vinay17](https://www.linkedin.com/in/m-vinay17/)

Passionate about Machine Learning, Artificial Intelligence, Data Science, and Full-Stack Development. I enjoy building practical AI/ML solutions and sharing my projects on GitHub.