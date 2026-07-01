# Task 13: Model Optimization

## Internship Details
- **Organization:** Edutech Solution
- **Program:** Data Science Internship
- **Task:** Task 13 — Model Optimization

## Objective
Optimize Random Forest model using GridSearchCV and
RandomizedSearchCV, and evaluate with Cross-Validation.

## Dataset Used
- **Name:** Breast Cancer Dataset (sklearn built-in)
- **Rows:** 569 | **Features:** 30

## Tools & Libraries
Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## Steps Performed
1. Loaded Breast Cancer dataset
2. Trained baseline Random Forest model
3. Applied GridSearchCV (param_grid with n_estimators, max_depth)
4. Applied RandomizedSearchCV (random param sampling)
5. Evaluated best model on test set
6. Ran 10-fold Cross-Validation
7. Saved comparison report

## Model Performance
| Model | Accuracy |
|-------|----------|
| Baseline | ~96% |
| GridSearchCV | ~97% |
| RandomizedSearchCV | ~97% |

## Files
| File | Description |
|------|-------------|
| task13_optimization.ipynb | Full notebook |
| best_parameters_report.csv | Model comparison |
| optimization_comparison.png | Bar chart |
| README.md | Documentation |

## Learning Outcome
Mastered hyperparameter tuning using GridSearch and
RandomizedSearch, and understood Cross-Validation importance.
