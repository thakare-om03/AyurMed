# AyurMed

AyurMed is a unique project that combines the ancient wisdom of Ayurveda with the power of modern Machine Learning to provide personalized healthcare solutions.

## Project Description

AyurMed takes into account individual factors such as disease, gender, age, prakruti (Ayurvedic constitution), and diabetic status to recommend personalized Ayurvedic remedies. This project aims to make Ayurvedic healthcare more accessible and easy to use in the digital age.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib
- Jupyter Notebook

## How to Run

1. Clone this repository.
2. Install the necessary Python libraries mentioned in `requirements.txt`.
3. Run the Jupyter Notebook.

## Code Overview

The code begins by importing the necessary libraries and loading the Ayurveda dataset. It then preprocesses the data by encoding categorical variables and dropping unnecessary columns. 

The preprocessed data is used to train an XGBoost classifier. The trained model is then used to predict Ayurvedic remedies for custom inputs.

The code also includes a section for visualizing feature importance using XGBoost's built-in function.
