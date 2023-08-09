Welcome to the repository for my FIFA 21 player dataset cleaning project! This repository contains a raw dataset containing player information from FIFA 21. In this project, I've utilized the powerful Pandas and Numpy libraries in Python to clean and manipulate the dataset. Below is an overview of the steps I've taken:

Data Set Information
This dataset comprises a wealth of player data from FIFA 21. Each row in the dataset corresponds to a player, and the columns provide information about various attributes such as player height, weight, value, wage, release clause, and more. You can download the data from the following link: https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring

Data Cleaning and Manipulation
To make the dataset more usable and informative, I've performed the following cleaning and manipulation tasks: 
Converting Height and Weight Columns: I've converted the height and weight columns into numerical forms, allowing for easier analysis.

Removing Unnecessary Newline Characters: I've removed unnecessary newline characters from all columns that contain them, ensuring data consistency.

Converting Value, Wage, and Release Clause Columns: The 'Value', 'Wage', and 'Release Clause' columns were initially stored as strings. I've converted these columns into numerical formats by removing characters like 'M' for million and 'K' for thousand and then converting them to the appropriate numerical value (e.g., multiplying by 1,000,000 for millions).

Stripping Star Characters: Some columns contained 'star' characters to represent player ratings. I've stripped these star characters and converted the columns to numerical values, making them more suitable for analysis.


