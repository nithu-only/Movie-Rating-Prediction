# 🎮 Movie Rating Prediction

A machine learning project that predicts IMDb movie ratings based on structured metadata, including genre, duration, director success rate, actor popularity, and more. The goal is to leverage data science techniques to build an accurate rating prediction model.

## 📌 Features

- **Data Preprocessing**: Handling missing values, outlier detection, and data normalization.
- **Categorical Encoding**: Converting categorical data (e.g., genres, directors) into machine-readable format.
- **Feature Engineering**: Creating features like *Director Success Rate* and *Actor Popularity* for better model performance.
- **Model Building & Evaluation**: Training a regression model and measuring its accuracy with metrics.
- **Visualizations**: Data insights using charts and graphs.

## 🐂️ Project Structure

```
Movie-Rating-Prediction/
├── data/
│   └── IMDb_Movies_India.csv        # Dataset containing movie metadata
├── models/
│   └── movie_rating_model.pkl       # Saved trained model
├── visuals/
│   ├── feature_importance.png       # Visualization of important features
│   ├── actual_vs_predicted.png      # Actual vs predicted ratings plot
│   ├── top_directors.png            # Bar chart of top-rated directors
│   ├── top_actors.png               # Bar chart of top-rated actors
│   └── heatmap.png                  # Heatmap of feature correlations
├── notebooks/
│   └── movie_rating_prediction.ipynb  # Jupyter Notebook for model training & analysis
├── requirements.txt                 # Dependencies for running the project
└── README.md                        # Project documentation
```

## ⚙️ Tools & Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Data Processing: `Pandas`, `NumPy`
  - Machine Learning: `Scikit-learn`
  - Visualization: `Matplotlib`, `Seaborn`
  - Model Serialization: `Joblib`
  
## 🚀 Installation & Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Movie-Rating-Prediction.git
cd Movie-Rating-Prediction
```

### 2️⃣ Install Dependencies

Ensure you have **Python 3.x** installed, then run:

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook

Launch Jupyter Notebook and open the project:

```bash
jupyter notebook
```

Then navigate to **notebooks/movie_rating_prediction.ipynb** and execute the code cells.

## 📈 Model Performance & Evaluation

- **Regression Metrics**:
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
  - **R² Score (Coefficient of Determination)**

- **Visualizations**:
  - **Feature Importance**: Understanding which factors influence movie ratings the most.
  - **Actual vs Predicted Ratings**: Checking model accuracy with a scatter plot.
  - **Top Directors & Actors**: Analyzing which directors and actors receive higher ratings.
  - **Heatmap**: Correlation analysis of features in the dataset.

## 🤝 Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## 🐟 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

