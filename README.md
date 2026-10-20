# Student Performance Prediction

## About the Project
This is a Machine Learning project that predicts students' final mathematics grades using information about their study habits, family background, and other student characteristics.

The project uses the Student Performance dataset from the UCI Machine Learning Repository.

## Objectives
- Understand and analyze student performance data.
- Prepare data for Machine Learning.
- Train and compare prediction models.
- Evaluate model performance using suitable metrics.

## Dataset
- **Source:** UCI Machine Learning Repository
- **File:** `student-mat.csv`
- **Records:** 395 students
- **Features:** 32 input columns are available in the original dataset, including student and family information.
- **Target:** `G3`, the final mathematics grade.

The first model excludes `G1` and `G2` to avoid using previous grades as input features.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Machine Learning Models
1. Linear Regression
2. Random Forest Regressor
3. Tuned Random Forest Regressor

## Model Evaluation

The models were evaluated on the same test set.

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 3.395 | 4.196 | 0.141 |
| Random Forest | 3.193 | 3.981 | 0.227 |
| Tuned Random Forest | 3.091 | 3.918 | 0.302 |

The tuned Random Forest model performed best among the three tested models. Its MAE and RMSE were lower, and its R² score was higher.

However, the R² score of 0.302 indicates that the model still has limited predictive power.

## How to Run
1. Download or open the notebook in this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the `.ipynb` notebook.
4. Upload `student-mat.csv` when needed.
5. Run the notebook cells in order.

## Future Improvements
- Try other Machine Learning algorithms.
- Explore additional useful features.
- Compare models using cross-validation.
- Improve prediction accuracy.

## Conclusion
This project helped me learn dataset collection, exploratory data analysis, feature selection, model training, hyperparameter tuning, and model evaluation using Python and Machine Learning.

## Author
Sandesh Shinde

Created as a Machine Learning portfolio project.
