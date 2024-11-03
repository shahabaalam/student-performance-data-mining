# Student Performance Data Mining

This project explores factors affecting student academic performance using data mining and machine learning. Through exploratory data analysis (EDA) and predictive modeling, the project investigates key factors influencing student performance in Math, Reading, and Writing.

## Table of Contents
- [About the Project](#about-the-project)
- [Objective](#objective)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Limitations and Recommendations](#limitations-and-recommendations)
- [Contributing](#contributing)
- [License](#license)

## About the Project
The objective is to perform EDA and develop predictive models to classify and predict student performance levels. The findings highlight demographic, behavioral, and parental factors that can inform educational strategies.

## Objective
The project aims to identify key predictors of student performance and assess the effectiveness of using demographic and behavioral factors to predict academic outcomes.

## Dataset
- **Source**: [Kaggle: Students Exam Scores - Extended Dataset](https://www.kaggle.com/datasets/desalegngeb/students-exam-scores)
- **Description**: The dataset contains records of 30,641 students, including demographic information, academic performance, and behavioral factors.

### Dataset Attributes:
- **Demographics**: Gender, Ethnic Group, Parental Education, etc.
- **Behavioral Features**: Weekly Study Hours, Participation in Sports, Lunch Type, etc.
- **Academic Scores**: Math, Reading, Writing scores.

## Methodology
1. **Data Preprocessing**: Cleaning, handling missing values, and encoding categorical variables.
2. **EDA**: Analyzing distributions, correlations, and patterns among features.
3. **Model Building**: Regression models to predict overall academic performance.
4. **Model Evaluation**: Comparison of performance metrics across models.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-data-mining.git
   ```
## Usage
- **Run the notebook**: Open `Student_Performance_EDA_and_Prediction.ipynb` for the full analysis and model building steps.
- **Scripts**: The `scripts` folder contains `data_processing.py` and `model_training.py` for data cleaning and model training.

## Results
The EDA and predictive modeling reveal that individual subject scores are the strongest predictors of academic success, while demographic and behavioral factors provide limited improvement.

## Limitations and Recommendations
- **Limitations**: Additional demographic features had limited predictive power. Non-linear models could potentially improve prediction accuracy.
- **Recommendations**: Focus on core academic support and consider regular data updates for improved prediction.

## Contributing
Contributions are welcome! To contribute:

1. Fork the repo.
2. Create a branch (`git checkout -b feature/NewFeature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/NewFeature`).
5. Open a pull request.

## License
This project is open-source and available for modification under the MIT License.

