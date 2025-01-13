# Cuisine Prediction from Ingredients

## Project Overview

This project aims to predict the cuisine type of a recipe based on its list of ingredients. We utilize machine learning techniques to classify recipes into different cuisine categories, providing insights into culinary patterns and ingredient associations across various cultures.

## Features

- Data preprocessing and cleaning of recipe ingredients
- Exploratory data analysis to understand ingredient distributions and cuisine patterns
- Implementation of multiple machine learning models for cuisine classification:
  - Multinomial Naive Bayes
  - Random Forest
  - Support Vector Machine (SVM)
  - Neural Networks
- Model evaluation and performance comparison
- Prediction of cuisine type for new recipes

## Dataset

The dataset used in this project is sourced from Kaggle's "What's Cooking?" challenge. It contains recipes with their corresponding ingredients and cuisine labels.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/cuisine-prediction.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have the dataset files in the `data/` directory.
2. Run the Jupyter notebook `cuisine_prediction.ipynb` to see the full analysis and model training process.
3. Use the trained model to predict cuisines for new recipes by running:
   ```
   python predict_cuisine.py --ingredients "ingredient1,ingredient2,ingredient3"
   ```

## Results

Our best performing model achieved an accuracy of 75.60% on the test set, significantly outperforming the baseline. Detailed performance metrics and analysis can be found in the notebook.

## Future Work

- Implement more advanced natural language processing techniques
- Explore ensemble methods to improve prediction accuracy
- Develop a web application for real-time cuisine prediction

## Contributors

- Yashwanth Guidvada


Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/31529289/849e5c72-513f-40e2-a973-25cd8990c930/CS584-Cuisine-Prediction.pdf
[2] https://github.com/suraj5424/Cuisine-Prediction
[3] https://github.com/cejdan/Cuisine-prediction
[4] https://microsoft.github.io/ML-For-Beginners/pdf/readme.pdf
[5] https://github.com/hasan-kamal/Cuisine-Prediction
[6] https://arpan-pal.github.io/projcets/Cuisine_2022
[7] https://www.reddit.com/r/learnmachinelearning/comments/ucwt5v/p_customer_churn_machine_learning_project/
[8] https://pure.eur.nl/ws/portalfiles/portal/56914961/Automatic_classification_of_takeaway_food_outlet_cuisine_type_using_machine_deep_learning.pdf
[9] https://github.com/HannesHolste/recipe-cuisine-machine-learning
[10] https://oudatalab.com/cs5293sp20/projects/project3.html
[11] https://github.com/Goooo4it/Clementine-cuisine-prediction-project
[12] https://www.studocu.vn/vn/document/truong-dai-hoc-bach-khoa-ha-noi/structured-programming/550-machine-learning-projects-ideas/55971764
[13] https://www.kaggle.com/code/anjanatiha/cuisine-prediction
[14] https://github.com/VarshithaCVasireddy/Cuisine_Predictor
[15] https://gitlab.uwe.ac.uk/m2-kassem/ai.daesd/-/blob/main/README.md
[16] https://gitlab.sberlab.nsu.ru/p.popova1/food-balance-prediction/-/blob/f7f5adc94f3cf7c744d976959e4fd368ea8c721f/README.md
[17] https://git.wur.nl/yizhou.ma/food-extrudability-assessment-and-prediction/-/blob/master/README.md
[18] https://dagshub.com/Omdena/KanoNigeriaChapter_FoodPrices/src/6d1f4aabb93826506fe6f623301c04325eeef00d/README.md
[19] https://www.youtube.com/watch?v=DehKm9DYfYY
[20] https://github.com/bins0000/Cuisine-Predictor
[21] https://www.linkedin.com/posts/siem-h_zomato-data-analysis-and-predictionreadmemd-activity-7269994771891249152-IOFs
