# Mushroom Classification Predictor Using Render/Streamlit

This project uses machine learning to classify mushrooms as edible or poisonous based on physical characteristics. The model trained is a Decision Tree Classifier, which provides clear visualizations for understanding the decision-making process.

## Dataset Overview

The dataset features physical descriptions of mushrooms and is used to predict whether they are edible or poisonous. Key features include:
- Cap shape, cap surface, cap color
- Bruises, odor
- Gill attachment, gill spacing, gill size, gill color
- Stalk shape, stalk root, stalk surface above/below ring
- Stalk color above/below ring, veil type, veil color
- Ring number, ring type, spore print color
- Population, habitat

Missing values were handled appropriately, and categorical data were encoded using `LabelEncoder`.

## Model Training and Evaluation

The Decision Tree Classifier was trained with the following steps:
- Data was split into training and test sets.
- Features were encoded using `LabelEncoder`.
- The model was trained on the training set and evaluated on the test set.
- Model performance was further validated using 5-fold cross-validation.

### Results Summary
- The Decision Tree achieved an accuracy of approximately 99.25%.
- The confusion matrix and classification report provided detailed insights into the performance across classes.

## Usage

To run the analysis:
1. Clone the repository.
2. Ensure the dataset is in the correct directory.
3. Run the Jupyter notebook to train the model.
4. Use the Streamlit app to input mushroom features and predict edibility.
5. Use Render to put in production

## Quickstart

```bash
git clone https://github.com/GOSS-hash/ml-webapp-using-streamlit


## Contact
For inquiries or contributions, please contact [spomar36@gmail.com](mailto:spomar36@gmail.com).

## Production Services
This project can be deployed using various cloud services to enhance accessibility and maintainability:

- **AWS and Azure**: For data storage and serverless computing.
- **Google Cloud Platform (GCP)**: For scalable object storage and serverless function execution.
- **ML Operations**: Continuous training, data validation, and model monitoring to ensure the model's reliability over time.

## Development and Contributions
Developers are encouraged to contribute by improving the model's accuracy, optimizing the Streamlit app, or enhancing the data preprocessing steps. For contribution guidelines, please refer to the repository's `CONTRIBUTING.md`.


