Overview
This project analyzes a Zomato dataset to gain insights into restaurant ratings, locations, cuisines, and online order/book table facilities. The analysis includes data cleaning, transformation, and visualization using Python libraries: Pandas, NumPy, Matplotlib, and Seaborn.

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/zomato-data-analysis.git
Navigate to the project directory:
bash
Copy code
cd zomato-data-analysis
Install the required libraries:
bash
Copy code
pip install pandas numpy matplotlib seaborn
Usage
Place the zomato.csv file in the project directory.

Run the script:

bash
Copy code
python zomato_analysis.py
Code Explanation
Data Reading and Initial Inspection

Load the Zomato dataset and display the first few rows.
Check the dataset's shape and columns.
Data Cleaning

Drop unnecessary columns.
Handle missing values in the 'rate' column.
Standardize 'cost2plates' by removing commas.
Group less frequent restaurant types, locations, and cuisines into 'others'.
Data Transformation

Rename columns for clarity.
Fill missing values in 'rate' with the column mean.
Data Visualization

Visualize distributions and relationships in the data using count plots and box plots.
Generate bar plots for online order facilities, book table facilities, restaurant types, and total votes by location.
Visualizations
Online Order Distribution

Location Distribution

Book Table Distribution

Online Order vs Rate

Book Table vs Rate

License
This project is licensed under the MIT License. See the LICENSE file for details.

