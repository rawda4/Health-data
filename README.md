# Health-data

# Clean Stroke Prediction Dataset

This dataset is a cleaned and preprocessed version of the original healthcare stroke dataset. It is ready for modeling and machine learning tasks.

## 🔍 Features

- **gender** (encoded)
- **age** (scaled)
- **hypertension**
- **heart_disease**
- **ever_married** (encoded)
- **work_type** (encoded)
- **Residence_type** (encoded)
- **avg_glucose_level** (scaled)
- **bmi** (scaled)
- **smoking_status** (encoded)
- **stroke** (target)
- **age_group** (engineered)

## 🧹 Preprocessing Steps

- Handled missing values using **KNN imputation**
- Removed inconsistent values (e.g., 'Other' in gender)
- Scaled numerical features (age, bmi, avg_glucose_level)
- Encoded all categorical variables

## 📂 File

- `clean_model_ready_data.csv`: final preprocessed dataset

## 📈 Use Cases

This dataset is ideal for:
- Binary classification (stroke prediction)
- Feature importance analysis
- Imputation and preprocessing demonstrations

## 🔗 Author

Uploaded by [@rawdaqenawy](https://www.kaggle.com/rawdaqenawy)
