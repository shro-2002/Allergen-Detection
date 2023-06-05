# Allergen Chip Challenge

This repository contains the code and documentation for the Allergen Chip Challenge, a data challenge focused on personalized medicine in the field of molecular allergology. The challenge aims to create a diagnostic algorithm for allergic diseases based on the antibody profile (immunoglobulin E) developed by each patient in response to their environment.

## Dataset

The dataset used in this challenge is a collection of anonymized data from over 4,000 patients. It includes tabular data associated with image files. The dataset is provided by the French Society of Allergology (SFA) in collaboration with the Health Data Hub. The data consists of various features such as patient demographics, clinical data, and specific allergen information.

## Problem Statement

The challenge involves multi-label classification, where the goal is to predict multiple labels related to allergy presence, severity, respiratory allergies, food allergies, venom allergies, and specific types of allergies. The evaluation metric for the challenge is the F1 score.

## Repository Structure

-  `predictions.csv`: Thisfile contains the dataset predicted using the model. Due to privacy concerns, the actual data is not included in the repository.
- `notebook.ipynb`: This  notebook displays data preprocessing, model selection, training, hyperparameter tuning, testing, and explainability.
- `README.md`: The README file you are currently reading.

# Evaluation Criteria
The performance of the submitted models will be evaluated based on the accuracy of the predictions on the held-out test set using the F1 score. In addition to model performance, the jury will also consider criteria such as explainability and code quality.

### Contributing
If you would like to contribute to this project, you can follow the standard GitHub workflow:

### Fork the repository.
Create a new branch for your feature or bug fix.
Make the necessary changes and commit them.
Push the changes to your forked repository.
Submit a pull request to the main repository.
Please ensure that your code follows the project's coding conventions and includes appropriate documentation.

## License
MIT License

## Contact
If you have any questions or need further information, please contact the organizers of the Allergen Chip Challenge.


