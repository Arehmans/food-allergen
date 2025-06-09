#Title
Real-time food allergen detection using OCR-enhanced machine learning techniques

#Description
This project presents a machine learning-based system that identifies allergens in packaged food items using OCR and text classification.
It integrates image preprocessing, text recognition (OCR), and a classification model to detect potential allergens in real-time.

#Dataset Information
The dataset of food ingredients and allergies is sourced from Kaggle [\cite{Dataset}](https://www.kaggle.com/datasets/uom190346a/food-ingredients-and-allergens). 
The dataset consists of a collection of information regarding allergens present in various food items.
 The data has information about allergy-related ingredients in different food items. 
 The dataset consists of 400 records and 7 attributes, each representing a specific food item and its associated allergens. 
 A detailed list of all the allergens present in the food products is included in the dataset. 
These allergens include a broad spectrum of foods, including dairy, wheat, and nuts (almonds, peanuts, pine nuts), 
seafood (anchovies, fish, shellfish), grains (oats, rice), ingredients derived from plants (celery, mustard, soybeans), 
animals (pork, poultry), and common components (cocoa, eggs). 
Additionally, the dataset contains entries where no specific allergens are listed. Following Table shows some key attributes for this dataset.

| **Attribute**   | **Description**                                                                       |
| --------------- | ------------------------------------------------------------------------------------- |
| Food Product    | Contains information about food products.                                             |
| Main Ingredient | Describes the primary food ingredients.                                               |
| Sweetener       | Indicates the type or presence of a sweetener used.                                   |
| Fat/Oil         | Specifies the type or presence of fat or oil used.                                    |
| Seasoning       | Lists spices or seasonings added to enhance flavor.                                   |
| Allergens       | Lists allergens associated with the product, indicating potential allergic reactions. |
| Prediction      | Label for the food product based on ingredients and allergens.                        |

/src/ML.ipynb
Performs allergen classification using machine learning and deep learning models. It includes feature extraction techniques such as TF-IDF, GloVe, and Bag of Words (BoW) for traditional machine learning models.

/src/DL.ipynb
Contains deep learning experiments with various learning rates and batch sizes, analyzing their impact on model performance.
#Usage Instructions

# Step 1: Clone repo
git clone https://github.com/Arehmans/food-allergen.git

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run system
Just open notebook and run all cells.

