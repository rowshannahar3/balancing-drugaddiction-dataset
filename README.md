# balancing-drugaddiction-dataset
A machine learning project focused on balancing a dataset to address class imbalance in drug addiction frequency analysis. This project implements data preprocessing, dataset balancing techniques, and evaluates the balanced dataset using a Decision Tree Classifier. The project includes cross-validation and confusion matrix visualizations, built with Python, Pandas, Scikit-learn, and Matplotlib.

## Dataset
The dataset includes 24 features, such as:
- **Demographic Features**: Age, Gender, Education
- **Social and Behavioral Features**: Enjoyable with, Live with, Spend most time, Friends influence
- **Psychological Features**: Mental/emotional problem, Suicidal thoughts, Failure in life
- **Drug-Related Features**: Ever taken drug, Frequency of drug usage, Easy to control use of drug

The target variable is `Frequency of drug usage`, which may exhibit class imbalance, addressed through balancing techniques in this project.

## Requirements
To run the notebook, you need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `google-colab` (for Google Drive integration, optional if running locally)

Install the dependencies using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
