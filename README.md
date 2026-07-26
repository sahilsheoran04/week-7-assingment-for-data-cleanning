&#x20;**Python Data Cleaning using Pandas**



&#x20;**Objective**



The objective of this assignment was to learn the basics of Python and Pandas by loading a CSV file, exploring the dataset, cleaning the data, and saving the cleaned dataset as a new CSV file.



&#x20;**Dataset**



\- \*\*Dataset Name:\*\* Sample - Superstore.csv



This dataset contains sales information such as customer details, product details, sales, quantity, discount, and profit.



**Steps Performed**



&#x20;1. Loaded the Dataset

\- Imported the Pandas library.

\- Uploaded the CSV file into Google Colab.

\- Loaded the dataset into a Pandas DataFrame.



&#x20;2. Explored the Dataset

I explored the dataset using different Pandas functions like:

\- `head()`

\- `tail()`

\- `shape`

\- `columns`

\- `dtypes`

\- `info()`

\- `describe()`



These functions helped me understand the structure of the dataset.



&#x20;3. Checked Missing Values

I checked the dataset for missing values using `isnull().sum()`. The dataset did not contain any missing values, so no cleaning was required in this step.



&#x20;4. Performed Basic Operations

I performed some basic operations on the dataset such as:

\- Selecting specific columns

\- Filtering rows based on different conditions

\- Displaying required records



&#x20;5. Removed Duplicate Records

I checked for duplicate rows using `duplicated()` and removed them using `drop\_duplicates()`.



6\. Created a New Column

The dataset did not contain a \*\*Price\*\* column, so I first calculated the price using:



`Price = Sales / Quantity`



Then I created a new column:



`total\_amount = Price × Quantity`



&#x20;7. Saved the Cleaned Dataset

\###Finally, I saved the cleaned dataset as:



`cleaned\_superstore.csv`



Files Included



\- `Data\_Cleaning\_Assignment.ipynb`

\- `Sample - Superstore.csv`

\- `cleaned\_superstore.csv`

\- `README.md`



&#x20;What I Learned



Through this assignment, I learned:

\- How to read CSV files using Pandas.

\- How to explore a dataset.

\- How to check and handle missing values.

\- How to filter rows and select columns.

\- How to remove duplicate records.

\- How to create new columns using existing data.

\- How to save a cleaned dataset as a new CSV file.



**Conclusion**



This assignment helped me understand the basic data cleaning process using Pandas. I learned how to work with a real dataset and perform common data preprocessing tasks before analysis.



\---



Name: Sahil Sheoran  

College : DPGU PUNE

